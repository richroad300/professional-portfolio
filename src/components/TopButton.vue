<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const isVisible = ref(false)

const checkScroll = () => {
  isVisible.value = window.scrollY > 300
}

const scrollToTop = () => {
  window.scrollTo({
    top: 0,
    behavior: 'smooth',
  })
}

onMounted(() => {
  window.addEventListener('scroll', checkScroll)
})

onUnmounted(() => {
  window.removeEventListener('scroll', checkScroll)
})
</script>

<template>
  <button
    v-if="isVisible"
    type="button"
    class="top-btn"
    aria-label="맨 위로 이동"
    @click="scrollToTop"
  >
    ↑
  </button>
</template>

<style scoped>
.top-btn {
  position: fixed;
  right: 30px;
  bottom: 30px;
  z-index: 100;

  width: 52px;
  height: 52px;

  border: none;
  border-radius: 50%;

  background: #111827;
  color: #ffffff;

  font-size: 24px;
  font-weight: 700;

  cursor: pointer;

  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.18);
  transition: 0.3s;
}

.top-btn:hover {
  background: #2563eb;
  transform: translateY(-4px);
}

@media (max-width: 768px) {
  .top-btn {
    right: 20px;
    bottom: 20px;

    width: 46px;
    height: 46px;

    font-size: 22px;
  }
}
</style>
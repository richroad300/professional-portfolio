<script setup>
import Header from './components/Header.vue'
import TopButton from './components/TopButton.vue'
import Home from './pages/Home.vue'
</script>

<template>
  <div class="app">
    <Header />
    <Home />
    <TopButton />
  </div>
</template>

<style scoped>
* {
  box-sizing: border-box;
}

.app {
  max-width: 1200px;
  margin: 0 auto;
  padding: 40px;
  color: #111827;
  font-family:
    -apple-system,
    BlinkMacSystemFont,
    "Pretendard",
    "Segoe UI",
    sans-serif;
}

@media (max-width: 768px) {
  .app {
    padding: 24px;
  }
}
</style>
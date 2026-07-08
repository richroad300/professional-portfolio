<template>
  <section class="hero">
    <div class="hero__bg"></div>

    <div class="hero__content">
      <p class="eyebrow">PORTFOLIO 2026</p>

      <h1>
        이상윤
        <span>UI Publisher<br />Project Leader · Project Manager</span>
      </h1>

      <p class="desc">
        13년 이상의 UI 퍼블리싱 경험을 바탕으로 금융, 공공, SI 프로젝트에서
        웹표준과 웹접근성을 고려한 UI를 구현했습니다.
      </p>

      <div class="actions">
        <a href="#projects" class="btn primary">Projects</a>
        <a href="https://github.com/richroad300" target="_blank" class="btn secondary">
          GitHub →
        </a>
      </div>
    </div>

    <div class="hero__stats" aria-label="career highlights">
      <div class="stat-card">
        <strong>13+</strong>
        <span>Years Experience</span>
      </div>

      <div class="stat-card">
        <strong>Finance</strong>
        <span>금융권 UI 프로젝트</span>
      </div>

      <div class="stat-card">
        <strong>Public</strong>
        <span>공공 · SI 프로젝트</span>
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero {
  position: relative;
  display: grid;
  grid-template-columns: 1.4fr 0.8fr;
  gap: 80px;
  align-items: center;
  min-height: calc(100vh - 120px);
  padding: 90px 0;
  overflow: hidden;
}

.hero__bg {
  position: absolute;
  top: 40px;
  right: -120px;
  z-index: -1;
  width: 520px;
  height: 520px;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(37, 99, 235, 0.14), transparent 65%);
}

.eyebrow {
  color: #2563eb;
  font-size: 14px;
  font-weight: 800;
  letter-spacing: 3px;
}

h1 {
  margin-top: 20px;
  font-size: clamp(48px, 7vw, 86px);
  line-height: 1.05;
  letter-spacing: -3px;
}

h1 span {
  display: block;
  margin-top: 18px;
  color: #6b7280;
  font-size: clamp(22px, 3vw, 34px);
  line-height: 1.35;
  letter-spacing: -1px;
}

.desc {
  margin-top: 34px;
  max-width: 700px;
  color: #4b5563;
  font-size: 18px;
  line-height: 1.85;
}

.actions {
  display: flex;
  gap: 14px;
  margin-top: 44px;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 52px;
  padding: 0 30px;
  border-radius: 999px;
  font-size: 16px;
  font-weight: 800;
  transition:
    transform 0.25s ease,
    background 0.25s ease,
    color 0.25s ease,
    border-color 0.25s ease;
}

.btn:hover {
  transform: translateY(-3px);
}

.primary {
  background: #111827;
  color: #ffffff;
}

.primary:hover {
  background: #2563eb;
}

.secondary {
  border: 1px solid #d1d5db;
  color: #111827;
}

.secondary:hover {
  border-color: #111827;
  background: #111827;
  color: #ffffff;
}

.hero__stats {
  display: grid;
  gap: 18px;
}

.stat-card {
  position: relative;
  padding: 30px;
  border: 1px solid #e5e7eb;
  border-radius: 28px;
  background: rgba(255, 255, 255, 0.82);
  box-shadow: 0 24px 60px rgba(17, 24, 39, 0.08);
  backdrop-filter: blur(12px);
}

.stat-card::before {
  content: "";
  position: absolute;
  inset: 0;
  border-radius: 28px;
  background: linear-gradient(135deg, rgba(37, 99, 235, 0.08), transparent 45%);
  pointer-events: none;
}

.stat-card strong {
  display: block;
  font-size: 36px;
  line-height: 1.2;
  letter-spacing: -1px;
}

.stat-card span {
  display: block;
  margin-top: 8px;
  color: #6b7280;
  font-size: 15px;
}

@media (max-width: 1024px) {
  .hero {
    grid-template-columns: 1fr;
    gap: 52px;
    min-height: auto;
  }

  .hero__stats {
    grid-template-columns: repeat(3, 1fr);
  }
}

@media (max-width: 768px) {
  .hero {
    padding: 64px 0;
  }

  .actions {
    flex-direction: column;
  }

  .btn {
    max-width: 100%;
  }

  .hero__stats {
    grid-template-columns: 1fr;
  }

  .stat-card {
    padding: 24px;
  }
}
</style>
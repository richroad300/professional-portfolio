<template>
  <section class="hero">
    <div class="hero-left">
      <p class="eyebrow">PORTFOLIO 2026</p>

      <p class="hello">안녕하세요.</p>

      <h1>이상윤</h1>

      <p class="role">UI Publisher · PL · PM</p>

      <p class="desc">
        13년 이상의 UI 퍼블리싱 경험을 바탕으로 금융, 공공, SI 프로젝트에서
        웹표준과 웹접근성을 고려한 UI를 구현했습니다.
      </p>

      <div class="actions">
        <a href="#projects" class="primary">Projects →</a>
        <a href="https://github.com/richroad300" target="_blank" class="secondary">
          GitHub →
        </a>
      </div>
    </div>

    <div class="hero-right">
      <div class="hero-card">
        <div class="hero-item">
          <strong>13+</strong>
          <span>Years Experience</span>
        </div>

        <div class="hero-item">
          <strong>20+</strong>
          <span>Projects</span>
        </div>

        <div class="hero-item">
          <strong>Finance · Public · SI</strong>
          <span>Project Experience</span>
        </div>

        <div class="hero-item">
          <strong>Web Standard · Accessibility</strong>
          <span>Publishing Strength</span>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 80px;
  min-height: calc(100vh - 120px);
  padding: 80px 0 120px;
}

.hero-left {
  flex: 1;
}

.hero-right {
  width: 400px;
}

.eyebrow {
  color: #2563eb;
  font-size: 14px;
  font-weight: 700;
  letter-spacing: 3px;
}

.hello {
  margin-top: 30px;
  color: #4b5563;
  font-size: 22px;
  font-weight: 600;
}

.hero-left h1 {
  margin-top: 14px;
  color: #111827;
  font-size: 82px;
  line-height: 1.05;
  letter-spacing: -2px;
}

.role {
  margin-top: 18px;
  color: #111827;
  font-size: 28px;
  font-weight: 700;
}

.desc {
  max-width: 640px;
  margin-top: 30px;
  color: #6b7280;
  font-size: 18px;
  line-height: 1.9;
}

.actions {
  display: flex;
  gap: 14px;
  margin-top: 44px;
}

.actions a {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  height: 52px;
  padding: 0 28px;
  border-radius: 30px;
  text-decoration: none;
  font-size: 16px;
  font-weight: 700;
  transition: .3s;
}

.primary {
  background: #111827;
  color: #fff;
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
  color: #fff;
}

.hero-card {
  padding: 42px;
  border: 1px solid #e5e7eb;
  border-radius: 30px;
  background: #fff;
  box-shadow: 0 24px 60px rgba(0, 0, 0, .06);
}

.hero-item {
  padding: 24px 0;
  border-bottom: 1px solid #f3f4f6;
}

.hero-item:first-child {
  padding-top: 0;
}

.hero-item:last-child {
  padding-bottom: 0;
  border-bottom: 0;
}

.hero-item strong {
  display: block;
  color: #111827;
  font-size: 30px;
  line-height: 1.35;
}

.hero-item span {
  display: block;
  margin-top: 8px;
  color: #6b7280;
  font-size: 15px;
}

@media (max-width: 768px) {
  .hero {
    flex-direction: column;
    align-items: flex-start;
    gap: 50px;
    min-height: auto;
    padding: 60px 0 90px;
  }

  .hero-right {
    width: 100%;
  }

  .hero-left h1 {
    font-size: 52px;
  }

  .role {
    font-size: 22px;
  }

  .desc {
    font-size: 16px;
  }

  .actions {
    flex-direction: column;
    width: 100%;
  }

  .actions a {
    width: 100%;
  }

  .hero-card {
    padding: 30px;
  }
}
</style>
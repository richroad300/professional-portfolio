<template>
  <section id="about" class="about">
    <div class="about__title">
      <p class="sub-title">ABOUT ME</p>
      <h2>성장하는 UI Publisher</h2>
    </div>

    <div class="about__content">
      <div class="experience">
        <strong>13+</strong>
        <span>Years Experience</span>
      </div>

      <div class="info">
        <div class="info-item">
          <h3>UI Publishing</h3>
          <p>웹표준, 웹접근성, 반응형 웹 구현</p>
        </div>

        <div class="info-item">
          <h3>Project Experience</h3>
          <p>금융 · 공공 · SI 프로젝트 다수 수행</p>
        </div>

        <div class="info-item">
          <h3>Career Goal</h3>
          <p>UI Publisher에서 PL · PM으로 성장 중</p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.about {
  padding: 120px 0;
}

.sub-title {
  color: #2563eb;
  font-size: 15px;
  font-weight: 700;
  letter-spacing: 2px;
}

.about h2 {
  margin-top: 12px;
  font-size: 42px;
}

.about__content {
  display: flex;
  justify-content: space-between;
  gap: 80px;
  margin-top: 60px;
}

.experience {
  min-width: 220px;
}

.experience strong {
  display: block;
  font-size: 90px;
  line-height: 1;
  color: #111827;
}

.experience span {
  display: block;
  margin-top: 12px;
  font-size: 22px;
  color: #6b7280;
}

.info {
  flex: 1;
}

.info-item + .info-item {
  margin-top: 40px;
}

.info-item h3 {
  margin-bottom: 10px;
  font-size: 24px;
}

.info-item p {
  color: #6b7280;
  font-size: 17px;
  line-height: 1.8;
}

@media (max-width: 768px) {
  .about {
    padding: 80px 0;
  }

  .about h2 {
    font-size: 32px;
  }

  .about__content {
    flex-direction: column;
    gap: 40px;
  }

  .experience strong {
    font-size: 64px;
  }

  .experience span {
    font-size: 18px;
  }

  .info-item h3 {
    font-size: 20px;
  }

  .info-item p {
    font-size: 16px;
  }
}
</style>
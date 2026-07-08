<template>
  <section id="projects" class="projects">
    <div class="section-title">
      <p>PROJECTS</p>
      <h2>주요 프로젝트</h2>
    </div>

    <div class="project-list">
      <article class="project-card">
        <div class="project-top">
          <span class="category">Public</span>
          <span class="date">2025.08 - 2025.12</span>
        </div>

        <h3>한국교육시설안전원 대국민 포털</h3>

        <p class="desc">
          공공 포털 UI 퍼블리싱을 100% 담당했으며, 웹표준과 웹접근성을 고려한 화면 구현을 수행했습니다.
        </p>

        <div class="info">
          <span>Role : UI Publisher</span>
          <span>Tech : HTML5, CSS3, JavaScript</span>
        </div>
      </article>

      <article class="project-card">
        <div class="project-top">
          <span class="category">Medical</span>
          <span class="date">2024.11 - 2025.05</span>
        </div>

        <h3>국립암센터 차세대 시스템</h3>

        <p class="desc">
          반응형 UI 퍼블리싱을 수행하고, 다양한 화면 구조에 맞춰 웹표준 기반 UI를 구현했습니다.
        </p>

        <div class="info">
          <span>Role : UI Publisher</span>
          <span>Tech : HTML5, CSS3, jQuery</span>
        </div>
      </article>

      <article class="project-card">
        <div class="project-top">
          <span class="category">Finance</span>
          <span class="date">2024.07 - 2024.09</span>
        </div>

        <h3>Kbank API 프로젝트</h3>

        <p class="desc">
          금융 서비스 환경에 맞춘 반응형 UI 퍼블리싱을 진행하고, 화면 품질을 유지하며 일정에 맞춰 작업했습니다.
        </p>

        <div class="info">
          <span>Role : UI Publisher</span>
          <span>Tech : HTML5, CSS3, JavaScript</span>
        </div>
      </article>

      <article class="project-card">
        <div class="project-top">
          <span class="category">Finance</span>
          <span class="date">2020.03 - 2023.04</span>
        </div>

        <h3>웰컴금융그룹</h3>

        <p class="desc">
          금융권 운영 및 구축 프로젝트에서 UI 퍼블리싱을 담당하고, 운영 이슈 대응 및 신규 화면 작업을 수행했습니다.
        </p>

        <div class="info">
          <span>Role : UI Publisher</span>
          <span>Tech : HTML5, CSS3, jQuery</span>
        </div>
      </article>
    </div>
  </section>
</template>

<style scoped>
.projects {
  padding: 120px 0;
}

.section-title {
  margin-bottom: 60px;
}

.section-title p {
  color: #2563eb;
  font-size: 15px;
  font-weight: 700;
  letter-spacing: 2px;
}

.section-title h2 {
  margin-top: 12px;
  font-size: 42px;
}

.project-list {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 30px;
}

.project-card {
  padding: 34px;
  border: 1px solid #e5e7eb;
  border-radius: 24px;
  background: #fff;
  transition: .3s;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 20px 50px rgba(0, 0, 0, .08);
}

.project-top {
  display: flex;
  justify-content: space-between;
  gap: 16px;
  margin-bottom: 28px;
}

.category {
  padding: 7px 13px;
  border-radius: 30px;
  background: #eff6ff;
  color: #2563eb;
  font-size: 13px;
  font-weight: 700;
}

.date {
  color: #6b7280;
  font-size: 14px;
}

.project-card h3 {
  font-size: 26px;
  line-height: 1.4;
}

.desc {
  margin-top: 20px;
  color: #4b5563;
  font-size: 16px;
  line-height: 1.8;
}

.info {
  display: flex;
  flex-direction: column;
  gap: 8px;
  margin-top: 28px;
  padding-top: 24px;
  border-top: 1px solid #f3f4f6;
}

.info span {
  color: #6b7280;
  font-size: 14px;
}

@media (max-width: 768px) {
  .projects {
    padding: 80px 0;
  }

  .section-title h2 {
    font-size: 32px;
  }

  .project-list {
    grid-template-columns: 1fr;
  }

  .project-card {
    padding: 28px;
  }

  .project-top {
    flex-direction: column;
  }

  .project-card h3 {
    font-size: 22px;
  }
}
</style>
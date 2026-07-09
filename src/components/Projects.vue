<template>
  <section id="projects" class="projects">
    <div class="section-title">
      <p>PROJECTS</p>
      <h2>대표 프로젝트</h2>
    </div>

    <div class="project-list">
      <article class="project-card">
        <div class="thumb">
            <span>Project Preview</span>
        </div>
        <div class="project-head">
          <span class="category">Public</span>
          <span class="date">2025.08 - 2025.12</span>
        </div>

        <h3>한국교육시설안전원 대국민 포털</h3>

        <p class="desc">
          공공 포털 UI 퍼블리싱을 100% 담당하고, 웹표준과 웹접근성을 고려한 화면 구현을 수행했습니다.
        </p>

        <dl class="project-info">
          <div>
            <dt>Role</dt>
            <dd>UI Publisher</dd>
          </div>
          <div>
            <dt>Work</dt>
            <dd>공통 UI, 화면 퍼블리싱, 반응형 대응</dd>
          </div>
          <div>
            <dt>Tech</dt>
            <dd>HTML5 · CSS3 · JavaScript</dd>
          </div>
        </dl>
      </article>

      <article class="project-card">
        <div class="thumb">
            <span>Project Preview</span>
        </div>
        <div class="project-head">
          <span class="category">Medical</span>
          <span class="date">2024.11 - 2025.05</span>
        </div>

        <h3>국립암센터 차세대 시스템</h3>

        <p class="desc">
          다양한 화면 구조에 맞춘 반응형 UI 퍼블리싱을 수행하고, 웹표준 기반의 화면 품질을 관리했습니다.
        </p>

        <dl class="project-info">
          <div>
            <dt>Role</dt>
            <dd>UI Publisher</dd>
          </div>
          <div>
            <dt>Work</dt>
            <dd>반응형 UI, 공통 컴포넌트, 화면 구현</dd>
          </div>
          <div>
            <dt>Tech</dt>
            <dd>HTML5 · CSS3 · jQuery</dd>
          </div>
        </dl>
      </article>

      <article class="project-card">
        <div class="thumb">
            <span>Project Preview</span>
        </div>
        <div class="project-head">
          <span class="category">Finance</span>
          <span class="date">2024.07 - 2024.09</span>
        </div>

        <h3>Kbank API 프로젝트</h3>

        <p class="desc">
          금융 서비스 환경에 맞춘 반응형 UI를 구현하고, 일정에 맞춰 화면 품질을 유지했습니다.
        </p>

        <dl class="project-info">
          <div>
            <dt>Role</dt>
            <dd>UI Publisher</dd>
          </div>
          <div>
            <dt>Work</dt>
            <dd>금융 UI 퍼블리싱, 반응형 화면 구현</dd>
          </div>
          <div>
            <dt>Tech</dt>
            <dd>HTML5 · CSS3 · JavaScript</dd>
          </div>
        </dl>
      </article>

      <article class="project-card">
        <div class="thumb">
            <span>Project Preview</span>
        </div>
        <div class="project-head">
          <span class="category">Finance</span>
          <span class="date">2020.03 - 2023.04</span>
        </div>

        <h3>웰컴금융그룹</h3>

        <p class="desc">
          금융권 운영 및 구축 프로젝트에서 UI 퍼블리싱을 담당하고, 운영 이슈와 신규 화면 작업에 대응했습니다.
        </p>

        <dl class="project-info">
          <div>
            <dt>Role</dt>
            <dd>UI Publisher</dd>
          </div>
          <div>
            <dt>Work</dt>
            <dd>운영 퍼블리싱, 신규 구축, UI 유지보수</dd>
          </div>
          <div>
            <dt>Tech</dt>
            <dd>HTML5 · CSS3 · jQuery</dd>
          </div>
        </dl>
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
.thumb {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 190px;
  margin-bottom: 26px;
  border-radius: 18px;
  background: #f3f4f6;
  color: #9ca3af;
  font-size: 15px;
  font-weight: 700;
}

.project-card:hover .thumb {
  background: #eff6ff;
  color: #2563eb;
}
.project-head {
  display: flex;
  justify-content: space-between;
  gap: 16px;
  margin-bottom: 26px;
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
  margin-top: 18px;
  color: #4b5563;
  font-size: 16px;
  line-height: 1.8;
}

.project-info {
  margin-top: 28px;
  padding-top: 24px;
  border-top: 1px solid #f3f4f6;
}

.project-info div {
  display: grid;
  grid-template-columns: 70px 1fr;
  gap: 16px;
  margin-top: 12px;
}

.project-info div:first-child {
  margin-top: 0;
}

.project-info dt {
  color: #111827;
  font-size: 14px;
  font-weight: 700;
}

.project-info dd {
  margin: 0;
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

  .project-head {
    flex-direction: column;
  }

  .project-card h3 {
    font-size: 22px;
  }
}
</style>
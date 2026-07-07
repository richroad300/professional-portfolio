<template>
  <section id="career" class="career">
    <div class="section-title">
      <p>CAREER</p>
      <h2>주요 경력</h2>
    </div>

    <div class="timeline">
      <div class="career-item">
        <span class="period">2025.08 - 2025.12</span>
        <div>
          <h3>한국교육시설안전원 대국민 포털</h3>
          <p>UI 퍼블리싱 100% 담당 · 공공 포털 UI 구현</p>
        </div>
      </div>

      <div class="career-item">
        <span class="period">2024.11 - 2025.05</span>
        <div>
          <h3>국립암센터 차세대 시스템</h3>
          <p>반응형 UI 퍼블리싱 · 웹표준 기반 화면 구현</p>
        </div>
      </div>

      <div class="career-item">
        <span class="period">2024.07 - 2024.09</span>
        <div>
          <h3>Kbank API 프로젝트</h3>
          <p>금융 서비스 화면 퍼블리싱 · 반응형 UI 구현</p>
        </div>
      </div>

      <div class="career-item">
        <span class="period">2020.03 - 2023.04</span>
        <div>
          <h3>웰컴금융그룹</h3>
          <p>금융권 운영 및 구축 프로젝트 UI 퍼블리싱</p>
        </div>
      </div>

      <div class="career-item">
        <span class="period">2018.09 - 2019.12</span>
        <div>
          <h3>현대백화점면세점</h3>
          <p>리뉴얼 및 운영 퍼블리싱 · 이벤트/운영 화면 대응</p>
        </div>
      </div>

      <div class="career-item">
        <span class="period">2012.05 - 2017.06</span>
        <div>
          <h3>넷컴바인</h3>
          <p>AXA, SKT, SK Btv, TV조선, 삼성 Smart TV 등 다수 프로젝트 수행</p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.career {
  padding: 120px 0;
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

.timeline {
  position: relative;
  margin-top: 60px;
  padding-left: 30px;
  border-left: 2px solid #e5e7eb;
}

.career-item {
  position: relative;
  display: grid;
  grid-template-columns: 180px 1fr;
  gap: 40px;
  padding-bottom: 44px;
}

.career-item::before {
  content: "";
  position: absolute;
  left: -39px;
  top: 4px;
  width: 14px;
  height: 14px;
  border: 3px solid #2563eb;
  border-radius: 50%;
  background: #ffffff;
}

.period {
  color: #2563eb;
  font-size: 15px;
  font-weight: 700;
}

.career-item h3 {
  font-size: 24px;
  margin-bottom: 8px;
}

.career-item p {
  color: #6b7280;
  font-size: 16px;
  line-height: 1.7;
}

@media (max-width: 768px) {
  .career {
    padding: 80px 0;
  }

  .section-title h2 {
    font-size: 32px;
  }

  .timeline {
    padding-left: 22px;
  }

  .career-item {
    grid-template-columns: 1fr;
    gap: 10px;
    padding-bottom: 36px;
  }

  .career-item::before {
    left: -31px;
  }

  .career-item h3 {
    font-size: 20px;
  }
}
</style>
<template>
  <section id="projects" class="projects">
    <div class="section-title">
      <p>PROJECTS</p>
      <h2>주요 프로젝트</h2>
    </div>

    <div class="project-list">

      <article class="project-card">
        <span class="date">2025.08 - 2025.12</span>

        <h3>한국교육시설안전원</h3>

        <p class="company">
          대국민 포털 구축
        </p>

        <p class="desc">
          UI 퍼블리싱 100% 담당<br>
          공통 UI 구축 및 웹접근성 적용
        </p>

        <span class="tag">Public</span>
      </article>

      <article class="project-card">
        <span class="date">2024.11 - 2025.05</span>

        <h3>국립암센터</h3>

        <p class="company">
          차세대 시스템 구축
        </p>

        <p class="desc">
          반응형 퍼블리싱<br>
          웹표준 기반 화면 구현
        </p>

        <span class="tag">Medical</span>
      </article>

      <article class="project-card">
        <span class="date">2024.07 - 2024.09</span>

        <h3>Kbank</h3>

        <p class="company">
          API 프로젝트
        </p>

        <p class="desc">
          금융 서비스 UI 퍼블리싱<br>
          반응형 화면 구현
        </p>

        <span class="tag">Finance</span>
      </article>

      <article class="project-card">
        <span class="date">2020.03 - 2023.04</span>

        <h3>웰컴금융그룹</h3>

        <p class="company">
          운영 및 구축
        </p>

        <p class="desc">
          운영 퍼블리싱<br>
          신규 구축 프로젝트 참여
        </p>

        <span class="tag">Finance</span>
      </article>

    </div>
  </section>
</template>

<style scoped>

.projects{
    padding:120px 0;
}

.section-title{
    margin-bottom:60px;
}

.section-title p{
    color:#2563eb;
    font-size:15px;
    font-weight:700;
    letter-spacing:2px;
}

.section-title h2{
    margin-top:12px;
    font-size:42px;
}

.project-list{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:30px;
}

.project-card{

    padding:36px;

    border:1px solid #e5e7eb;

    border-radius:20px;

    transition:.3s;
}

.project-card:hover{

    transform:translateY(-8px);

    box-shadow:0 18px 45px rgba(0,0,0,.08);

}

.date{

    color:#2563eb;

    font-size:14px;

    font-weight:700;

}

.project-card h3{

    margin-top:18px;

    font-size:28px;

}

.company{

    margin-top:10px;

    font-weight:600;

}

.desc{

    margin-top:22px;

    color:#6b7280;

    line-height:1.8;

}

.tag{

    display:inline-block;

    margin-top:28px;

    padding:8px 14px;

    background:#eff6ff;

    color:#2563eb;

    border-radius:30px;

    font-size:14px;

    font-weight:700;

}

@media(max-width:768px){

.project-list{

grid-template-columns:1fr;

}

.section-title h2{

font-size:32px;

}

}

</style>
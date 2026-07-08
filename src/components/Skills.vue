<template>
  <section id="skills" class="skills">
    <div class="section-title">
      <p>SKILLS</p>
      <h2>기술 역량</h2>
    </div>

    <div class="skill-list">
      <article class="skill-card">
        <h3>Front-End</h3>
        <ul>
          <li>HTML5</li>
          <li>CSS3</li>
          <li>JavaScript</li>
          <li>jQuery</li>
          <li>Vue3 <span>Learning</span></li>
        </ul>
      </article>

      <article class="skill-card">
        <h3>Publishing</h3>
        <ul>
          <li>Responsive Web(반응형 웹)</li>
          <li>Web Accessibility(웹접근성)</li>
          <li>Web Standards(웹표준)</li>
          <li>Cross Browsing(크로스 브라우징)</li>
        </ul>
      </article>

      <article class="skill-card">
        <h3>Collaboration</h3>
        <ul>
          <li>Git</li>
          <li>SVN</li>
          <li>Figma</li>
          <li>Zeplin</li>
          <li>Photoshop</li>
        </ul>
      </article>
    </div>
  </section>
</template>

<style scoped>
.skills {
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

.skill-list {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 28px;
}

.skill-card {
  padding: 34px;
  border: 1px solid #e5e7eb;
  border-radius: 22px;
  background: #fff;
  transition: 0.3s;
}

.skill-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 18px 45px rgba(0, 0, 0, 0.08);
}

.skill-card h3 {
  margin-bottom: 24px;
  font-size: 24px;
}

.skill-card ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.skill-card li {
  padding: 12px 0;
  border-bottom: 1px solid #f3f4f6;
  color: #4b5563;
  font-size: 16px;
}

.skill-card li:last-child {
  border-bottom: 0;
}

.skill-card span {
  margin-left: 6px;
  color: #2563eb;
  font-size: 13px;
  font-weight: 700;
}

@media (max-width: 768px) {
  .skills {
    padding: 80px 0;
  }

  .section-title h2 {
    font-size: 32px;
  }

  .skill-list {
    grid-template-columns: 1fr;
  }
}
</style>
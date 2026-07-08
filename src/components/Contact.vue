<template>
  <section id="contact" class="contact">
    <div class="section-title">
      <p>CONTACT</p>
      <h2>함께 일할 준비가 되어 있습니다.</h2>
    </div>

    <div class="contact-list">
      <a href="mailto:fafl7@naver.com" class="contact-card">
        <span>📧 Email</span>
        <strong>fafl7@naver.com</strong>
      </a>

      <a href="https://github.com/richroad300" target="_blank" class="contact-card">
        <span>💻 GitHub</span>
        <strong>github.com/richroad300</strong>
      </a>

      <div class="contact-card">
        <span>📱 Phone</span>
        <strong>010-4627-7394</strong>
      </div>
    </div>
  </section>
</template>

<style scoped>
.contact {
  padding: 120px 0;
}

.section-title {
  margin-bottom: 50px;
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

.contact-list {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
}

.contact-card {
  display: block;
  padding: 32px;
  border: 1px solid #e5e7eb;
  border-radius: 22px;
  color: #111827;
  text-decoration: none;
  transition: .3s;
}

.contact-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 18px 45px rgba(0, 0, 0, .08);
}

.contact-card span {
  display: block;
  color: #6b7280;
  font-size: 15px;
}

.contact-card strong {
  display: block;
  margin-top: 14px;
  font-size: 18px;
}

@media (max-width: 768px) {
  .contact {
    padding: 80px 0;
  }

  .section-title h2 {
    font-size: 32px;
  }

  .contact-list {
    grid-template-columns: 1fr;
  }

  .contact-card {
    padding: 26px;
  }
}
</style>
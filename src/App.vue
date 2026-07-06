<template>
  <div class="app">
    <header class="header">
      <div class="logo">SY Portfolio</div>

      <nav class="nav">
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Career</a>
        <a href="#">Projects</a>
        <a href="#">Skills</a>
        <a href="#">Contact</a>
      </nav>
    </header>

    <main class="hero">
      <p class="hello">안녕하세요.</p>

      <h1>
        이상윤<br />
        <span>UI Publisher · PL · PM</span>
      </h1>

      <p class="desc">
        13년 이상의 UI 퍼블리싱 경험을 바탕으로 금융, 공공, SI 프로젝트에서
        웹표준과 웹접근성을 고려한 UI 구현을 수행했습니다. 현재는 PL과 PM까지
        역할을 확장하고 있습니다.
      </p>

      <button class="btn">프로젝트 보기</button>
    </main>
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

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 22px;
  font-weight: 700;
}

.nav {
  display: flex;
  gap: 28px;
}

.nav a {
  color: #4b5563;
  text-decoration: none;
  font-size: 15px;
}

.nav a:hover {
  color: #111827;
}

.hero {
  margin-top: 120px;
}

.hello {
  color: #2563eb;
  font-weight: 700;
  margin-bottom: 20px;
}

h1 {
  margin: 0;
  font-size: 64px;
  line-height: 1.2;
  letter-spacing: -1.5px;
}

h1 span {
  font-size: 32px;
  color: #6b7280;
}

.desc {
  max-width: 680px;
  margin-top: 32px;
  color: #4b5563;
  font-size: 18px;
  line-height: 1.8;
}

.btn {
  margin-top: 40px;
  padding: 15px 30px;
  border: 0;
  border-radius: 14px;
  background: #111827;
  color: #ffffff;
  font-size: 16px;
  cursor: pointer;
}

.btn:hover {
  background: #2563eb;
}

@media (max-width: 768px) {
  .app {
    padding: 24px;
  }

  .header {
    align-items: flex-start;
    gap: 24px;
    flex-direction: column;
  }

  .nav {
    flex-wrap: wrap;
    gap: 14px 20px;
  }

  .hero {
    margin-top: 80px;
  }

  h1 {
    font-size: 42px;
  }

  h1 span {
    font-size: 22px;
  }

  .desc {
    font-size: 16px;
  }
}
</style>
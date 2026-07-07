<template>
  <main class="hero">
    <p class="hello">안녕하세요.</p>

    <h1>
      이상윤
      <span>UI Publisher · PL · PM</span>
    </h1>

    <p class="desc">
      13년 이상의 UI 퍼블리싱 경험을 바탕으로 금융, 공공, SI 프로젝트에서
      웹표준과 웹접근성을 고려한 UI 구현을 수행했습니다.
      <br />
      현재는 PL과 PM까지 역할을 확장하고 있습니다.
    </p>

    <button class="btn">프로젝트 보기</button>
  </main>
</template>

<style scoped>
.hero {
  margin-top: 120px;
}

.hello {
  color: #2563eb;
  font-size: 18px;
  font-weight: 700;
}

h1 {
  margin-top: 20px;
  font-size: 64px;
  line-height: 1.2;
}

h1 span {
  display: block;
  margin-top: 10px;
  font-size: 30px;
  color: #6b7280;
}

.desc {
  margin-top: 30px;
  max-width: 650px;
  color: #6b7280;
  font-size: 18px;
  line-height: 1.8;
}

.btn {
  margin-top: 45px;
  padding: 16px 34px;
  border: none;
  border-radius: 14px;
  background: #111827;
  color: #fff;
  font-size: 16px;
  font-weight: 600;
  cursor: pointer;
}

.btn:hover {
  background: #2563eb;
}

@media (max-width: 768px) {
  .hero {
    margin-top: 70px;
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
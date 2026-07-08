<template>
  <header class="header">
    <h1 class="logo">
      <a href="#">SY Portfolio</a>
    </h1>

    <div class="right-menu">
      <nav class="nav">
        <a href="#about">About</a>
        <a href="#career">Career</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
      </nav>

      <a href="#" class="resume-btn">
        Resume
      </a>
    </div>
  </header>
</template>

<style scoped>
.header {
  position: sticky;
  top: 0;
  z-index: 50;

  display: flex;
  justify-content: space-between;
  align-items: center;

  padding: 20px 0;

  background: rgba(255, 255, 255, .9);
  backdrop-filter: blur(12px);
}

.logo {
  margin: 0;
  font-size: 22px;
  font-weight: 700;
}

.logo a {
  color: #111827;
  text-decoration: none;
}

.right-menu {
  display: flex;
  align-items: center;
  gap: 22px;
}

.nav {
  display: flex;
  gap: 28px;
}

.nav a {
  color: #4b5563;
  text-decoration: none;
  font-size: 15px;
  font-weight: 500;
}

.nav a:hover {
  color: #111827;
}

.resume-btn {
  padding: 10px 18px;
  border: 1px solid #111827;
  border-radius: 30px;
  color: #111827;
  text-decoration: none;
  font-size: 14px;
  font-weight: 700;
  transition: .3s;
}

.resume-btn:hover {
  background: #111827;
  color: #fff;
}

@media (max-width: 768px) {
  .header {
    align-items: flex-start;
    gap: 20px;
    flex-direction: column;
  }

  .right-menu {
    align-items: flex-start;
    flex-direction: column;
    gap: 16px;
  }

  .nav {
    flex-wrap: wrap;
    gap: 14px 20px;
  }
}
</style>
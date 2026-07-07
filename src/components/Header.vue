<template>
  <header class="header">
    <h1 class="logo">
      <a href="/">SY Portfolio</a>
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
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 0;
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

.nav {
  display: flex;
  align-items: center;
  gap: 28px;
}

.nav a {
  position: relative;
  color: #4b5563;
  font-size: 15px;
  font-weight: 500;
  text-decoration: none;
  transition: color .25s ease;
}

.nav a:hover {
  color: #111827;
}

.nav a::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: -6px;
  width: 0;
  height: 2px;
  background: #2563eb;
  transition: width .25s ease;
}

.nav a:hover::after {
  width: 100%;
}

.right-menu {
  display: flex;
  align-items: center;
  gap: 20px;
}

.resume-btn {
  padding: 10px 18px;
  border: 1px solid #111827;
  border-radius: 30px;
  color: #111827;
  text-decoration: none;
  transition: .3s;
}

.resume-btn:hover {
  background: #111827;
  color: #fff;
}

@media (max-width: 768px) {
  .header {
    flex-direction: column;
    align-items: flex-start;
    gap: 20px;
  }

  .nav {
    flex-wrap: wrap;
    gap: 14px 20px;
  }
  .right-menu{
    flex-direction:column;
    align-items:flex-start;
  }
}
</style>
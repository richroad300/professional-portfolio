<template>
  <footer class="footer">
    <p>© 2026 이상윤. All rights reserved.</p>

    <div class="footer-links">
      <a href="mailto:sylee840516@gmail.com">Email</a>
      <a href="https://github.com/richroad300" target="_blank">GitHub</a>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 40px 0;
  border-top: 1px solid #e5e7eb;
  color: #6b7280;
}

.footer-links {
  display: flex;
  gap: 20px;
}

.footer-links a {
  color: #111827;
  text-decoration: none;
  font-weight: 700;
}

.footer-links a:hover {
  color: #2563eb;
}

@media (max-width: 768px) {
  .footer {
    align-items: flex-start;
    flex-direction: column;
    gap: 16px;
  }
}
</style>
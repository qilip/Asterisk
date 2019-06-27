<template>
  <footer class="n-footer">
    <div class="footer-container">
      &copy; {{ new Date().getFullYear() }} <a href="https://qilip.io" target="_blank">qilip</a>
    </div>
  </footer>
</template>

<style>
.n-footer {
  font-weight: 300;
  font-size: 16px;
  color: #CED4DA;
  word-spacing: 2px;
  padding-bottom: 10px;
}

.footer-container > a:link {
  color: inherit;
  text-decoration: none;
}

.footer-container > a:visited {
  color: inherit;
  text-decoration: none;
}

.footer-container > a:hover {
  color: inherit;
  text-decoration: underline;
}

.footer-container > a:active {
  color: #46C3FA;
  text-decoration: none;
}
</style>

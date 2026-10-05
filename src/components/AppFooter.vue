<template>
  <footer class="footer">
    <p>
      Developed by
      <a href="https://softmarmot.com" target="_blank" rel="noopener">softmarmot.com</a>
    </p>
  </footer>
</template>

<style scoped>
.footer {
  margin-top: 3rem;
  padding-top: 1rem;
  border-top: 1px solid var(--color-border);
  font-size: 12px;
  text-align: center;
  color: var(--color-text);
}

@media (min-width: 1024px) {
  .footer {
    grid-column: 1 / -1;
    margin-top: 2rem;
    padding-bottom: 1rem;
  }
}
</style>

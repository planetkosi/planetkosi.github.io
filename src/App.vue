<template>
  <main class="page">
    <h1>Hello from Vue.js</h1>
    <p>Your GitHub Pages site is now configured for Vue.</p>
  </main>
</template>

<style scoped>
  :global(body) {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0f172a;
    color: #e2e8f0;
  }

  .page {
    min-height: 100vh;
    display: grid;
    place-items: center;
    text-align: center;
    padding: 2rem;
  }

  h1 {
    margin-bottom: 0.5rem;
    font-size: clamp(2rem, 5vw, 4rem);
  }

  p {
    margin: 0;
    font-size: 1.1rem;
    opacity: 0.9;
  }
</style>

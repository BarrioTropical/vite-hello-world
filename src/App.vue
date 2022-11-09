<script setup>
import AppTitleVue from './components/AppTitle.vue';
</script>

<template>
  <header>
    <div class="wrapper">
      <AppTitleVue msg= "La mia prima app con Vite!" />
    </div>
  </header>

  <main>
    <AppTitleVue />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}



@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: center;
    flex-wrap: wrap;
    color: white;
  }
}
</style>

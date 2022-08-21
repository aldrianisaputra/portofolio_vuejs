<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Personal from './components/Personal.vue'
</script>

<template>
  <header>
      <nav>
        <RouterLink to="/personal">Personal</RouterLink>
        <RouterLink to="/skill">Skill</RouterLink>
      </nav>
  </header>

  <RouterView />
</template>

<style scoped>

.logo {
  display: block;
  margin: 0 auto 2rem;
  border-radius: 10px;
  
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
  
}

nav a{
  margin-left: 18px;
}

nav a.router-link-exact-active {
  color: white;
  background-color: #AE7978;
}

nav a.router-link-exact-active:hover {
  /* background-color: transparent; */
  
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  /* border-left: 1px solid var(--color-border); */
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2)
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    /* flex-wrap: wrap; */
    
    
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    
  }
}
</style>

<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>

<div class="nav">
      <nav>
        <RouterLink to="/personal">Personal</RouterLink>
        <RouterLink to="/skill">Skill</RouterLink>
      </nav>
</div>

  <RouterView />
</template>

<style scoped>


nav {
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
  
}

nav a{
  margin-left: 9px;
}

nav a.router-link-exact-active {
  color: white;
  background-color: #AE7978;
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
    align-items: center;
    padding-right: calc(var(--section-gap) / 2)
  
  }


  nav {
    text-align: right;
    margin-right: 1rem;
    font-size: 1rem;

    padding: 1rem 0;
    
  }
}
</style>

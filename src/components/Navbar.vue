<template>
    <div class="container1">
        <div class="container">
            <div class="nav">
                <nav>
                    <RouterLink to="/personal">Personal</RouterLink>
                    <RouterLink to="/skill">Skill</RouterLink>
                </nav>
            </div>
        </div>
    </div>
</template>

<!-- <script>
export default {
    name: "footer"
};
</script> -->

<style scoped>
.container1 {
    background-color: #ffcdcc;
    width: 120;
    height: 60px;
    margin: 0px 40px 7px 40px;
    border-radius: 10px;
}

.a {
    color: white;

}
nav {
  font-size: 12px;
  margin: 0px 5px;
  /* background: black;
  border-radius: 5px;
  width: 100%; */
  
}

nav a{
  margin-left: 9px;
}

nav a.router-link-exact-active {
  color: white;
  background-color: #AE7978;
  border-radius: 5px;
}



nav a {
  display: inline-block;
  padding: 0 2rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    align-items: center;
    padding-left: calc(var(--section-gap) / 2)
  
  }


  nav {
    text-align: right;
    margin-right: 1rem;
    font-size: 1rem;

    padding: 1rem 0;
    
  }
}
</style>
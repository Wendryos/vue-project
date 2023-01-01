<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
<div class="container-gg">
  <div class="container-list">
    <RouterView />
  </div>

  <div class="container-footer">
    <nav>
      <RouterLink to="/"> Lista de sopas nº 1 </RouterLink> /
      <RouterLink to="/list"> Lista de sopas nº 2 </RouterLink>
    </nav>
  </div>
</div>

</template>

 <style scoped>

.container-gg {
  display: grid;
  width:  60%;
  height: 100%;
  margin: 0 auto;
}


.container-list {
  width: 100%;
  position: relative;
}


.container-footer {
  position: relative;
  margin: 0 auto;
}

nav a {
  text-decoration: none;
  color: rgb(11, 39, 92);
  font-size: 14px;
  font-weight: 1000;
  text-transform: uppercase;

}

</style>

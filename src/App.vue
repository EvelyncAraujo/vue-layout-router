<script setup>

</script>

<template>
  <header>HEADER</header>
  <aside>
    <nav class="menu">
      <router-link to="/">home</router-link>
      <router-link to="/about">about</router-link>
      <router-link to="/Contact">Contact</router-link>
      <router-link to="/p2">p2</router-link>
      <router-link to="/p3">p3</router-link>

    </nav>
  </aside>

  <main>
    <router-view />
  </main>

<footer>FOOTER</footer>
</template>

<style scoped>
.menu{
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
</style>

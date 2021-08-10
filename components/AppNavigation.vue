<template>
  <nav>
    <!-- <a href="/about">About</a> 
      <a href="/">Home</a> -->
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/about">About</NuxtLink>
    <NuxtLink to="/menu">Menu</NuxtLink>
  </nav>
</template>

<script>
export default {}
</script>

<style lang="postcss">
nav {
  position: relative;
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-end;
  padding: var(--padding);
  border-bottom: 1px solid var(--light-gray);

  a {
    margin-left: 40px;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }
}
</style>
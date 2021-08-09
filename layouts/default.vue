<template>
  <div>
    <AppNavigation />
    <nuxt />
    <AppFooter />
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
:root {
  --dark-gray: rgb(46, 46, 46);
  --light-gray: rgb(226, 226, 226);
  --padding: 20px;
  --text-title: 24px;
  --text-body: 16px;
  --bkg-color: rgb(206, 228, 241);
  --text-bold: 600;
  --text-line-height: 1.6;
}

a.nuxt-link-exact-active {
  font-weight: var(--text-bold);
}

body,
html {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Oxygen';
  text-decoration: none;
  color: var(--dark-gray);
  line-height: var(--text-line-height);
}

h1 {
  font-size: var(--text-title);
}

p {
  font-size: var(--text-body);
  width: 40vw;
}

a,
a:visited {
  color: var(--dark-gray);
}
</style>
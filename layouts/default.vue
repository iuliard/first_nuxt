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

<style lang="postcss">
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

.nuxt-link-exact-active {
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
}

h1 {
  font-size: var(--text-title);
}

p {
  font-size: var(--text-body);
  width: 40vw;
}

a {
  text-decoration: none;
  color: var(--dark-gray);
}

a:visited {
  color: var(--dark-gray);
}
/* Fade transition */
.fade-enter,
.fade-leave-to {
    opacity: 0;
}
.fade-enter-active,
.fade-leave-active {
    transition: opacity 0.4s;
}
</style>
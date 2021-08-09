<template>
  <div id="contact">
    <ul>
      <li><a href="http://">Instagram</a></li>
      <li><a href="http://">Twitter</a></li>
      <li><a href="http://">Are.na</a></li>
    </ul>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
#contact {
  width: 25vw;
  padding: var(--padding);
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  background-color: lightseagreen;

  ul {
    padding: 0 20px;
  }
}
</style>
<template>
  <div id="footer">
    <div class="container">
      <div class="inner">
        <div class="footer-col">
          <h4>REAL REVIEW</h4>
          <ul>
            <li><NuxtLink to="about">About</NuxtLink></li>
            <li><NuxtLink to="/menu">Menu</NuxtLink></li>
          </ul>
        </div>
        <div class="footer-col">
          <h4>CONNECT</h4>
          <ul>
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Instagram</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="postcss">
* {
  // margin: 0;
  // padding: 0;
  box-sizing: border-box;
}

#footer {
  position: absolute;
  bottom: 0;
  width: 100vw;
  height: auto;
  padding: var(--padding);
  border-top: 1px solid var(--light-gray);
  line-height: var(--text-line-height);

  .container {
    width: 20vw;
    margin-bottom: 50px;
  }

  .inner {
    display: flex;
    justify-content: space-between;
  }

  .footer-col {
    margin-right: 20px;
  }

  h4 {
    margin-bottom: 40px;
  }

  ul {
    list-style: none;
  }

  a:hover {
    text-decoration: underline;
  }

  .nuxt-link-exact-active {
    font-weight: var(--text);
  }
}
</style>
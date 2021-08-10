<template>
  <figure>
    <img :src="image" />
    <figcaption>
      {{ content }}
      <ul>
        <li v-for="detail in details" :key="detail.id">{{ detail }}</li>
      </ul>
    </figcaption>
  </figure>
</template>

<script>
export default {
  data() {
    return {
      content: 'Contents',
      image: './assets/img/real_review.png',
      details: ['Interviews', 'Reviews', 'Journal'],
    }
  },
}
</script>

<style lang="postcss">
ul {
  list-style: none;
  margin: auto;
}
</style>
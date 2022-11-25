<script>
export default {
  props: {
    img: String,
    title: String,
  },
};
</script>

<template>
  <div class="card">
    <img :src="img" :alt="title" />
    <h4>{{ title }}</h4>
  </div>
</template>

<style lang="scss" scoped>
.card {
  padding: 0.625rem;
}
img {
  width: 11.625rem;
  height: 11.625rem;
  object-fit: cover;
  object-position: top;
}
h4 {
  font-size: 0.875rem;
  text-align: start;
  margin-top: 0.3125rem;
}
</style>

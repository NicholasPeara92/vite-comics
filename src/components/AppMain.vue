<script>
import AppPrefooter from './AppPrefooter.vue';


export default {
  name: 'AppMain',
  components: {
    AppPrefooter
  },
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <main>
    <div class="container">
      <h2>-- Content goes here -- </h2>
    </div>
  </main>
  <AppPrefooter/>
</template>

<style scoped>
main {
  background-color: var(--secondary-color);
  color: white;
  height: 8.25rem;
}
</style>



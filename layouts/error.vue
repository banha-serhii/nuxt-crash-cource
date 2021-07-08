<template>
<section>
  <h1>Error 404</h1>
  <nuxt-link to='/'>
    <button>Home</button>
  </nuxt-link>
</section>
</template>

<script>
export default {
  name: 'error'
}
</script>

<style scoped>
section {
  width: 600px;
}
h1 {
  color: red;
}
</style>

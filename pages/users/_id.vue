<template>
<section>
  <h1>User {{$route.params.id}} </h1>

  <nuxt-link to='/users/'>
    <button>Back</button>
  </nuxt-link>
</section>
</template>

<script>
export default {
  validate({ params }) {

    return /^\d+$/.test(params.id)
  }
}
</script>

<style scoped>

</style>

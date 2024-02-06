<template>
  <div>
    <h2>About</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur
      adipisicing elit. Ea eum necessitatibus
      aliquid incidunt. Voluptatum ut vel similique
      iure porro sit?
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur
      adipisicing elit. Ea eum necessitatibus
      aliquid incidunt. Voluptatum ut vel similique
      iure porro sit?
    </p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
  const { data } = await useFetch(
    '/api/currency/USD'
  )
</script>

<style lang="scss" scoped>

</style>
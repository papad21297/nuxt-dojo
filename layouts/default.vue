<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p4 flex justify-between">
        <NuxtLink to="/" class="font-bold">Nuxt Page</NuxtLink>
        <ul class="flex gap-4">
          <li>
            <NuxtLink to="/">Home</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about">About</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/products" class="btn">Products</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/products/abc">abc product</NuxtLink>
          </li>
        </ul>
      </nav>
    </header>

    <!-- output the page content -->
    <div class="container mx-auto p-4">
      <slot />
    </div>
  </div>
</template>

<style scoped>
  .router-link-exact-active {
    color: #12B488;
  }
</style>
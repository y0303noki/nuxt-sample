<script>
export default {
  data() {
    return {
      greeting: 'Hello World!',
    }
  },
}
</script>

<template>
  <div>
    <p class="greeting">{{ greeting }}</p>
    <NuxtLink to="/">Home page</NuxtLink>
  </div>
</template>

<style>
.greeting {
  color: red;
  font-weight: bold;
}
</style>

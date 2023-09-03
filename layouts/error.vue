<template>
  <div class="container" style="margin-top: 200px;">
    <h1 v-if="error.statusCode === 404">Page not found</h1>
    <h1 v-else>An error occurred</h1>
    <NuxtLink to="/">Home page</NuxtLink>
  </div>
</template>
<script>
export default {
  layout: 'blog',
  // eslint-disable-next-line vue/require-prop-types
  props: ['error'], // Anda dapat membuat custom page untuk halaman error
}
</script>

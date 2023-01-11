<template>
  <div>
    <nav>
      <NuxtLink to="/">
        Home
      </NuxtLink>
      <NuxtLink to="/about">
        About
      </NuxtLink>
    </nav>

    <slot />

  </div>
</template>
<script>export default {
  components: {}
}
</script>
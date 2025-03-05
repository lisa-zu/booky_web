<script lang="ts">
  import Navigation from "@/components/navigation.vue"
  export default {
    name: 'DefaultLayout',
    components: {
      Navigation,
    }
  }
</script>

<template>
  <div>
    <Navigation />
    <main class="p-8">
      <slot />
    </main>
  </div>
</template>

<style scoped>
.header {
  background: #333;
  color: white;
  padding: 1rem;
  text-align: center;
}
</style>

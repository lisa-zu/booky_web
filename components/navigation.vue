<script lang="ts">
  export default {
    name: "Navigation",
    data() {
      const links = [
        {
          label: "Home",
          // icon: "",
          // avatar: { src: "" },
          to: "/"
        },
        {
          label: "Suche",
          // icon: "",
          // avatar: { src: "" },
          to: "/search"
        }
      ]
      return {
        links
      }
    }
  }
</script>

<template>
  <UHorizontalNavigation :links="links" class="border-b border-gray-200 dark:border-gray-800" />
</template>
<script setup>
  // import "@styles/index.css"
  import "@styles/test.less"
  import classes from "@styles/test.module.css"
</script>

<template>
  <div :class="[`root ${classes.moduleClass}`]">Hello Vite</div>
</template>

<style scoped>

</style>

<script setup>
import { NResult, NButton } from "naive-ui";
import { RouterLink } from "vue-router";
console.log(404);
</script>

<template>
  <n-result
    status="404"
    title="404 Not Found"
    description="Looks like you've got lost!"
  >
    <template #footer>
      <n-button>
        <router-link to="/">Take me home</router-link>
      </n-button>
    </template>
  </n-result>
</template>

<style scoped>
a {
  text-decoration: none;
}
</style>

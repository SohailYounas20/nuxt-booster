<template>
  <div>{{ text }}</div>
  <button @click="checking">click me</button>
</template>

<script lang="ts" setup>
const text = ref("this is testing project for nuxt booster");
const checking = () => {
  console.log("checking");
  text.value = "button is clicked";
};
</script>

<script setup lang="ts">
defineProps({
  msg: String
})

</script>

<template>
  <div class="option-container">
    <label for="sandwichMax">샌드위치</label>
    <input id="sandwichMax" type="text" value="1">
    <label for="breadMax">빵</label>
    <input id="breadMax" type="text" value="1">
    {{ msg }}
  </div>
</template>

<style scoped>

</style>

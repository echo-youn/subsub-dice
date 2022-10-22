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
    <p class="hi">
      <p class="hello">{{ msg }}</p>
    </p>
  </div>
</template>

<style scoped lang="scss">
  .hi{
    color: red;
    .hello {
      color: yellow;
    }
  }
</style>

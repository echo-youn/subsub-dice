<script setup lang="ts">
defineProps({
  msg: String
})

</script>

<template>
  <div class="option-container">
    <h1 class="header"></h1>
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
  .header{
    background-image: url('../assets/subway_logo.png');
    background-repeat: no-repeat;
    background-size: contain;
    width: 300px;
    height: 100px;
    margin: 10px auto;
  }
</style>

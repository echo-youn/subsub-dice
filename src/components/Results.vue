<script setup lang="ts">
</script>

<template>
  <div class="result-container">
    <div class="result" id="result">
      <div class="main">
        <div class="mainMenu">
          <img src="../assets/italianBmt.png"/>
        </div>
        <p id="sandwich">sandwich</p>
      </div>
      <p id="sandwich">샌드위치: </p>
      <p id="bread">빵: </p>
      <p id="cheese">치즈: </p>
      <p id="vegitable">야채: </p>
      <p id="saltedVegitable">절임류: </p>
      <p id="sauce">소스: </p>
      <p id="extra">추가: </p>
    </div>
  </div>
</template>

<style scoped>
.main{
  text-align: center;
  border: 5px solid rgba(0, 148, 35, 0.3);
}
.main > p {
  margin: 0 auto;
  padding-bottom: 20px;
}
.mainMenu{
  width: 120px;
  height: 90px;
  border-radius: 50%;
  line-height: 100px;
}
.mainMenu > img{
  background-repeat: no-repeat;
  width: 100%;
  height: auto;
  vertical-align: middle;
}
</style>

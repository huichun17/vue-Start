<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import ButtonView from './components/ButtonView.vue';//import 後為自定義變數,基本上都會跟檔案名相同

</script>

<template>
  <div class="container">
    <h1>HI</h1>
    <ButtonView/>
    <ButtonView/>
    <ButtonView/>
    <div class="ButtonView"></div>
    
    
  </div>

</template>

<style scoped>
.container{
  background-color: grey;
  width: 100vw;
  height: 100vh;
  padding: 16px;
  display: flex;
  justify-content:space-around;
}

.ButtonView{
  height: 20%;
  width: 20%;
  background-color: aquamarine;
}

</style>

<template>
  <div class="app">
  <div class="content">
   <div class="loader">
   <img width="100" src="./assets/web-loader.gif" alt="loader">
   <br>
   <div style="text-align:center">Loading...</div>
   </div>
  </div>
</div>
</template>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.content{
  background: rgb(243, 243, 243);
  widows: 100%;
 height: 100vh;
 display: flex;
 justify-content: center;
 align-items: center;
}

.loader{
  width: 100px;
  height: auto
}
</style>

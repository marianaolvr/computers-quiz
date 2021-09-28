<template>
  <div id="app">
    <div class="title">
      <h1>COMPUTER QUIZ</h1>
    </div>
    <router-view/>
  </div>
</template>

<style>
* {
  padding: 0;
  margin: 0;
  border: 0;
  box-sizing: border-box;
}

#app {
  background-image: url('../src/assets/computer-image.jpg');
  background-size: 100% 100%;
  height: 100vh;
}

.title {
  padding-top: 21px;
  text-align: center;
  font-family: 'Staatliches', cursive;
  color: #2c3e50;
}
</style>

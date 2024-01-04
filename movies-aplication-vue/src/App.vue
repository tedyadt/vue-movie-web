<template>
  <header></header>
  <router-view/>
</template>

<style lang="scss">
@font-face {
  font-family: Roboto;
  font-style: normal;
  font-display: swap;
  font-weight: 10;
  src: url('@/assets/fonts/Roboto/Roboto-Regular.ttf');
}

#app {
  font-family: 'Roboto';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  background-color: #9BBEC8;
}

header {
  width: 1600px;
  height: 65px;
  left: 0px;
  top: 0px;
  background: #164863;
  margin-bottom: 60px;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
@import'~bootstrap/dist/css/bootstrap.css'
</style>

<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'App',

  data: () => {
    return {
    }
  }
}
</script>

<style>
html, body{
  height: 100% ;
  width: 100%;
  margin: 0;
}

@font-face {
  font-family: "Avenir";
  src: url('./assets/avenirnextcyr-light.ttf');
}
@font-face {
  font-family: "Avenir Bold";
  src: url('./assets/avenirnextcyr-bold.ttf');
}
h1, h2, h3, span, p {
  font-family: "Avenir";
}
</style>

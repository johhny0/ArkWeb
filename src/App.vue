<template>
  <div id="nav" class="bg-default">
    <router-link :to="{ name: 'Home' }">Home</router-link> |
    <router-link :to="{ name: 'About' }">About</router-link> |
    <router-link :to="{ name: 'Login' }">Login</router-link>
  </div>
  <router-view />
</template>

<style>
@font-face {
  font-family: "OpenSans";
  font-weight: 400;
  font-style: normal;
  font-display: auto;
  unicode-range: U+000-5FF;
  src: local("OpenSans"),
    url("./assets/fonts/open-sans/OpenSans-Regular.ttf") format("truetype");
}

body {
  font-family: "OpenSans";
}
</style>

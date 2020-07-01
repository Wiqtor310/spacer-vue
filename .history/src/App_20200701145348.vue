<template>
  <div class="app">
    <div class="nav">
      <router-link to="/home">spacer</router-link>
      <router-link to="/about">about</router-link>
    </div>
    <router-view to="/home" />
  </div>
</template>

<style scoped>
</style>

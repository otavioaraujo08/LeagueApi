<template>
  <div class="container">
    <router-view/>
  </div>
</template>

<style>
  * {
    margin: 0;
  }

  .container {
    background: rgb(29,24,42);
    background: linear-gradient(90deg, rgba(29,24,42,1) 0%, rgba(26,26,65,1) 51%, rgba(4,69,83,1) 100%);
    color: white;
  }
</style>

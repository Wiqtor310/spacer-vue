<template>
  <div class="wrapper">
    <div class="serach">
      <label for="search">Search</label>
      <input id="search" name="search">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
};
</script>

<style>
  .wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0;
    padding: 30px;
    width: 100%;
  }

  .search {
    display: flex;
    flex-direction: column;
    width: 300px;
  }

  label {
    font-family: Montserrat, sans-serif;
  }

  input {
    height: 30px;
    border: 0;
    border-bottom: 1px solid black;
  }
</style>

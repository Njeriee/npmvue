<script>
export default {
  data() {
    return {
      name: 'sav'
    }
  },
}
</script>

<template>
  <p class = 'hey'>hello {{ name }} welcome to Vue</p>
</template>

<style>
.hey{
  justify-content: center;
    position: absolute;
    top: 500px;
    left: 40%;
    font-size: 50px;
    font-family: Arial, Helvetica, sans-serif;
    background-color: yellowgreen;
}
</style>
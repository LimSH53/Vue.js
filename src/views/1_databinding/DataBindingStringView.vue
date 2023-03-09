<template>
  <div>
    <h1>Hello {{ userName }}</h1>
    <p></p>
  </div>
</template>
<script>
export default {
  data() {
    return {
      userName: 'suhyeon',
      message: 'hihi'
    }
  }
}
</script>
<style scoped>
.text-red {
  color: red;
}
</style>

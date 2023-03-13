<template>
  <div>
    <input type="text" name="" id="" v-bind:value="userId" readonly>
    <input type="text" name="" id="" :value="userId" readonly>
    <br>
    <img :src="imgSrc" alt="" style="widows: 100px; height: auto;">
    <br>
    <input type="search" name="" id="" v-model="txt1">
    <button :disabled="txt1 === ''">조회</button>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      userId: 'suheyon',
      imgSrc: 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS3kBJNOiNjCbgxLrjE1azwFvb24NXLVweQQA&usqp=CAU',
      txt1: ''
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>

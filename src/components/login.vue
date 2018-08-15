<template>
  <div class="login">
    <div class="text">{{msg}}</div>
    <el-input v-model="input" placeholder="请输入内容"></el-input>
  </div>
</template>

<script>
export default {
  name: 'Login',
  data () {
    return {
      msg: 'Welcome to Your Vue.js Manage App!!!',
      input: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.login {
  .text {
    font-size: 20px;
    font-weight: bold;
  }
}
</style>

<template>
  <div id='logindetail'>
      <el-input  v-model="input" placeholder="请输入你的邮箱"></el-input>
      <el-input placeholder="请输入密码" v-model="password" show-password></el-input>
  </div>
</template>

<script>
export default {
data(){
    return{
        input:'',
        password:''
    }
}
}
</script>

<style lang="less">
  
  
</style>
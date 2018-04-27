<template>
  <div>
    <div class="username">
      <label for="username">姓名：</label><input type="text" placeholder="输入用户名或者手机号" id="username">
    </div>
    <div class="password">
      <label for="password">密码：</label><input type="password" placeholder="输入密码" id="password">
    </div>
    <button @click="submit()">登录</button>

  </div>
</template>
<script>
  export default {
    name:'login',
    data(){
      return {

      }
    },
    methods:{
      submit(){
        alert(111111)
      }
    }
  }
</script>

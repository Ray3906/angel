<script setup>
import { ref } from 'vue';

ref
</script>

<template>
  <div>
    <h2>欢迎来到登录页面</h2>
    <p>tips:</p>
    <form action="#">
      <input type="text" id="userName" ref="userName" placeholder="用户名">
      <label for="text">密码</label>
      <input type="password" id="password" placeholder="密码">
      <input type="button" value="提交">
    </form>
  </div>
</template>
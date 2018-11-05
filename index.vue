<template>
  <div id="app">
    <div>
      <router-link to="/$app">跳转链接dd</router-link>
    </div>
    <!--路由容器-->
    <div>
      <router-view></router-view>
    </div>
    <img src="@/assets/logo.png">
    <footer>
      <div class="content">
        <p>
          Copyright © 2014-2017 www.asopendata.gov.cn All Rights Reserved<br>黔ICP备16010582号 网站访问量：<br>主办单位：XX市大数据发展管理委员会 建设单位：XX市信息产业发展中心<br>(建议使用Chrome、360浏览器(极速模式)，1366*768以上分辨率浏览本站)
        </p>
      </div>
    </footer>
  </div>
</template>

<script src="./index.js"></script>

<style src="./index.css"></style>

<!--足迹-->
<template>
  <div class="footprint">
    <v-head title_head="我的足迹" goBack="true" bgColor="#f4f4f4"></v-head>
    <div class="info_container">
      <img src="../../../assets/nothing.png">
      <span class="tip">漫漫美食路，一个脚印也没留下</span>
      <p class="text">美食排着队 等你去品尝</p>
    </div>
  </div>
</template>

<script>
</script>

<style rel="stylesheet/scss" lang="scss" scoped>
  .footprint {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: #fff;
    .info_container{
      text-align: center;
      position:absolute;
      top:50%;
      left:50%;
      transform: translate(-50%,-50%);
      img{
        width:3rem;
        height:3rem;
      }
      .tip{
        display: block;
        font-size:0.35rem;
      }
      .text{
        font-size:0.3rem;
        color:#333;
        margin-top:0.3rem;
      }
    }
  }
</style>

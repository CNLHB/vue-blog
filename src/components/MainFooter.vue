<template>
  <section class="Footer-wrap">
    <footer class="footer-inner">
      <p> 廖华飚 Copyright&copy;  1348844909@qq.com</p>
      <p><a href="http://www.miit.gov.cn" target="_blank">备案号: 粤ICP备19093459号</a></p>
    </footer>
  </section>
</template>

<script>
  import {mapState, mapActions} from 'vuex';

  export default {
    data() {
      return {}
    },
  }
</script>

<style lang="scss" scoped>
  .footer-inner {
    padding: 64px 32px;
    line-height: 36px;
    text-align: center;
    font-size: 18px;
    color: #000000;
    background: #ffffff;
  }

  .footer-inner a {
    color: blue;
    text-decoration: none;
  }
</style>

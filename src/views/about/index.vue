<template>
  <section class="author">
    <article class="item">
      <h1 class="logo">
        <img src="../../assets/images/logo.jpg" alt="LOGO">
      </h1>
    </article>
    <article class="text">
      <p>
        我是廖华飚，现在是一名学生，未来是一名前端工程师，这个博客属于我的个人博客网站，github地址 <a href="https://github.com/CNLHB" target="_blank">
        Github </a>
      </p>
      <p class="content">博客的内容：记录个人学习路程</p>
      <p>博客的愿景：和更多的朋友一起学习进步。</p>
      <p>博客的风格：简约至上。</p>
    </article>
    <article class="end">
      <p>最后，祝大家每天开心，每天幸福！</p>
    </article>
  </section>
</template>

<script>
  export default {
    created() {
      document.title = `blog- liaohuabiao.com`
    }
  }
</script>

<style scoped lang="scss">
  .author {
    box-sizing: border-box;
    width: 70%;
    min-height: 73vh;
    margin: 24px auto;
    padding-bottom: 24px;
    background-color: white;
  }

  .item {
    width: 100%;
    padding: 48px 0;
    text-align: center;
    background: white;
  }

  .logo {
    width: 360px;
    margin: 0 auto;

    & img {
      width: 100%;
    }
  }

  a {
    color: #409EFF;
  }

  .text {
    padding: 0 24px 24px;
    line-height: 42px;
    font-size: 20px;
    color: #666;
    text-indent: 2em;
  }

  .content {
    padding-top: 24px;
  }

  .end {
    line-height: 42px;
    font-size: 20px;
    color: #666;
    text-indent: 2em;
  }

  @media screen and (min-width: 200px) and (max-width: 750px) {
    .author {
      width: 100%;
    }
  }
</style>

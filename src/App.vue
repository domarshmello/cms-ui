<template>
  <div id="app">
    <nav class="navbar is-info">
      <div class="navbar-menu">
        <div class="navbar-start">

          <router-link class="navbar-item" to="/">
            <img src="./assets/buttercms.jpg">
          </router-link>
        </div>
        <div class="navbar-end">
          <router-link class="navbar-item" to="/customers">
           用户
          </router-link>
          <router-link class="navbar-item" to="/category">
            栏目
          </router-link>
          <router-link class="navbar-item" to="/blog">
            文章
          </router-link>
          <router-link class="navbar-item" to="/media">
           媒体库
          </router-link>
          <router-link class="navbar-item" to="/question">
            调查问卷
          </router-link>
          <router-link class="navbar-item" to="/question">
            调查问卷
          </router-link>
        </div>
      </div>
    </nav>

    <router-view/>

    <footer class="footer">
      <div class="container">
        <div class="content has-text-centered">
          <p>
            <strong> cms </strong>  design by <a href="https://github.com/domarshmello">unicorn <i class="fab fa-github"></i></a>.
          </p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>


<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }

  footer.footer {
    margin-top: 10rem;
    padding-top: 1.5rem;
    padding-bottom: 1.5rem
  }
</style>

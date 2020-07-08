<template>
<nav class="navbar z-depth-3" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item nav-title" href="/">Mike Hood<span class="nav-subtitle">Software Engineer</span></a>
    <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>
  <div id="navbar" class="navbar-menu">
    <div class="navbar-start">
      <router-link to="/" class="navbar-item">Home</router-link>
      <router-link to="/about" class="navbar-item">About</router-link>
    </div>
  </div>
</nav>
</template>
<script>
export default {
  name: 'Nav',
  methods: {
  // Log the user in
  login() {
    this.$auth.loginWithRedirect();
  },
  // Log the user out
  logout() {
    this.$auth.logout({
      returnTo: window.location.origin
    });
  }
  }
}
</script>
<style lang="scss" scoped>
  nav {
    margin: 0;
    width: 100%;
    padding: .8rem;
    display: flex;
    background: linear-gradient(to left top, rgb(255, 255, 255), rgb(176, 237, 214));
    border-bottom: 2px solid black;
    border-top: 2px solid black;
    justify-content: space-between;
    align-items: center;
    font-family: 'Lato', sans-serif;
    img {
      width: 100vw;
    }
    a {
      display: flex;
      font-weight: bold;
      color: #2c3e50;
      &.router-link-exact-active {
        color: #d88d00;
      }
    }
    a:hover, .navbar-item {
      cursor: pointer;
    }
    .nav-title {
      color: black;
      text-shadow: 1.5px 1.5px whitesmoke;
      font-size: 2.5rem;
      font-weight: 300;
      .nav-subtitle {
        font-size: 1.5rem;
        padding: 0 0 0 6vw;
      }
    }
    .navbar-start {
      display: flex;
      justify-content: flex-end;
      align-items: center;
      a {
        padding: 0 2vw;
        font-size: 1.2rem;
        display: flex;
        align-items: center;
      }
    }
    .navbar-item {
      padding: .4rem;
      display: flex;
    }
  }
  @media only screen and (max-width: 600px) {
  nav {
    .nav-title {
      font-size: 1.4rem;
      .nav-subtitle {
        font-size: 1rem;
      }
    }
  }
}
</style>
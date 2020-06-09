<template>
  <b-navbar>
    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <img
          v-b-toggle.sidebar
          class="menu-icon"
          src="../../assets/img/menu-icon.svg"
          alt="menu icon"
        />
      </b-navbar-nav>
      <b-navbar-nav>
        <b-nav-item href="#">Cast</b-nav-item>
        <b-nav-item href="#">Storyline</b-nav-item>
        <b-nav-item href="#">Did You Know ?</b-nav-item>
        <b-nav-item href="#">Director's Trademarks</b-nav-item>
      </b-navbar-nav>
      <b-navbar-nav>
        <img class="search-icon" src="../../assets/img/search.svg" alt="menu icon" />
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>
<script>
export default {
  name: "NavBar"
};
</script>
<style scoped lang="scss">
.navbar {
    padding: 2.5rem 0;
}
.navbar-collapse {
  justify-content: space-between;
  .nav-item a {
      color: #fff;
      font-family: "Source Sans Pro";
      font-weight: bold;
      margin: 0 30px;
  }
}
.menu-icon {
  width: 30px;
}
.search-icon {
  width: 22px;
}
</style>
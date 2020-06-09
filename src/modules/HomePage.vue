<template>
  <div>
    <NavBar />
    <SideNav />
    <Description />
    <h1>Interstellar</h1>
    <section>
      <Facts />
      <Player />
    </section>
  </div>
</template>

<script>
import NavBar from "../components/navbar/NavBar";
import SideNav from "../components/sidebar/SideBar";
import Description from "../components/description/Description";
import Facts from "../components/facts/Facts";
import Player from "../components/player/Player";

export default {
  name: "HomePage",
  components: {
    NavBar,
    SideNav,
    Description,
    Facts,
    Player
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-family: "Mandatory Plaything";
  color: #fff;
  margin: 0;
  font-weight: 500;
  font-size: 6em;
}
section {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>

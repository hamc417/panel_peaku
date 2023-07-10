<template>
  <div class="position-base">
    <AppNavbar />
    <SideBar/> 
    <div class="position-list">
      <VacantesList :vacantes="vacantes" />

    </div>
  </div>
</template>

<script>
// import CardJob from './components/CardJob.vue';
import AppNavbar from './components/Navbar.vue';
import VacantesList from './components/VacantesList.vue';
import { vacantes } from './components/vacantes';
import SideBar from './components/SideBar.vue'

export default {
  name: 'App',
  components: {
    // CardJob,
    AppNavbar,
    VacantesList,
    SideBar,
  },
  computed: {
    vacantes() {
      return vacantes;
    },
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
ul{
  list-style: none;
}

.position-base{
  position: relative;
}

.position-list{
  position: absolute;
  top: 5rem;
  left: 8rem;
}
</style>

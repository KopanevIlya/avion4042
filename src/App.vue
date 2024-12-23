<template>
  <div class="main_container">
    <HeaderTop/>
    <nav class="nav-list">
      <router-link to="/">Plant pots</router-link> 
      <router-link to="/about">Ceramics</router-link> 
      <router-link to="/">Tables</router-link> 
      <router-link to="/">Chairs</router-link> 
      <router-link to="/">Crockery</router-link> 
      <router-link to="/">Tableware</router-link> 
      <router-link to="/">Cutlery</router-link> 
    </nav>
    <FirstBlock/>
    <MakesBlock/>
  </div>
</template>

<script>
import HeaderTop from './components/HeaderTop.vue';
import FirstBlock from './components/FirstBlock.vue';
import MakesBlock from './components/MakesBlock.vue';


export default{
  name:"App",
  components: {
    HeaderTop, FirstBlock, MakesBlock
  }
}
</script>


<style>

.main_container {
  margin: 0 auto;
  width: 1440px;
  font-family: sans-serif;
}

.bottom-navigation {
  height: 70px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.nav-list {
  display: flex;
  justify-content: center;
}

.nav-list a {
  text-decoration: none;
  color: #726E8D;
}

.nav-list li {
  margin-right: 44px;
}

</style>

<script >
import Header from './components/Header.vue' ;
import HomeView from './view/HomeView.vue' ;
export default
{
  name: "App",
  components: {
    Header,
    HomeView
  },
}

</script>

<template>
  <div>
    <Header />
    <HomeView />
  </div>
</template>

<style>
@import './assets/base.css';

</style>

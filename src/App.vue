<template>
<TheHeader/>
<router-view/>
<TheFooter/>
</template>

<script>
import TheHeader from "@/components/TheHeader.vue";
import TheFooter from "@/components/TheFooter.vue";

export default {
  components: { TheHeader, TheFooter },
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  height: 88.395vh;
}
.backgroundKiwi{
    background-image: url("@/assets/bg.png");
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}
</style>

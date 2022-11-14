<template>

<div class="home">   
    <HelloWorld />
  </div>
  
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style>
.home{
     height: 910px;
    background-image: url("https://www.clearvoice.com/wp-content/uploads/2018/06/06.14.18_Hero_1360x646-1140x542.png");
  background-size: cover;
    background-repeat:no-repeat;
    background-position: center center;


background-position: center center;
background-repeat: no-repeat;
background-attachment: fixed;
background-size: cover;
}
</style>
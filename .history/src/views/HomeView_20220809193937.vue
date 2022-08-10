<template>
  <div class="main-container">
    <Banner />
   <h1>HOME</h1>
   <p>Monte seu Burger</p>
  </div>
</template>

<script>
import Banner from "@/components/Banner.vue";

export default{
  name: "Home",
  components:{
    Banner
  }
}

</script>

<style>
.main-container{
  margin: 0;
}
</style>
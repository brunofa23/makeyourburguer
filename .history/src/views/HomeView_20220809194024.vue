<template>
  <div class="main-container">
    <Banner />
   <h1>Monte seu Burger:</h1>
   <p>Formulário</p>
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
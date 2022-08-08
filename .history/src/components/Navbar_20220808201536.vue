<template>
  <div id="nav">
    <router-link to="/" >
        <img :src="logo" :id="alt" >
    </router-link>
    <router-link to="/">Home</router-link> |
    <router-link to="/pedidos">Pedidos</router-link>
  </div>
</template>

<script>
export default {
    name:"Navbar",
    props:["logo", "alt"]
}
</script>

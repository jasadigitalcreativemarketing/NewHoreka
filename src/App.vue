<template>
  <div id="app">
    <div id="nav">
      <Navbar/>
      <router-view/>>
      <endFooter/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import endFooter from "@/components/footer.vue";

export default {
  name: 'home',
   components: {
    Navbar,endFooter
  }
}
</script>


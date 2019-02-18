<template>
  <div class="home">
    <Navbar/>
    <Jumbroton/>
    <section/>
    <endFooter/>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import Jumbroton from "@/components/jumbroton.vue";
import endFooter from "@/components/footer.vue";

export default {
  name: 'home',
   components: {
    Navbar,Jumbroton,endFooter
  }
}
</script>

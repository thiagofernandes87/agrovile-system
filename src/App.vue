<template>
  <Navbar :logo="logo_src" :alt="app_name"/>
  <router-view/>
  <Footer />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";
export default {
   components: {
     Navbar,
     Footer
   },
   data(){
     return{
       logo_src:"/img/logo.png",
       app_name:"Produzir"
     }
   }
}
</script>
<style>
 *{
   font-family: Helvetica;
   padding: 0;
   margin: 0;
   box-sizing: border-box;
 }

 .main-container{
   margin: 50px;
   min-height: 380px;
 }

 h1{
   
   font-size: 20px;
   margin-bottom: 30px;
   
 }

</style>

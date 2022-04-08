<template>
    <div id="nav">
        <router-link to="/" id="logo-url">
            <img :src="logo" :alt="alt" id="logo">
        </router-link> 
        <router-link to="/">Home</router-link> |
        <router-link to="/parceiros">Parceiros</router-link>
    </div>
</template>

<script>
export default {
    name: "Navbar",
    props: ["logo", "alt"]
}
</script>

<style scoped>
 #nav{
     background-color: #52b69a;
     border-bottom: 2px solid #76c893;
     padding: 5px 10px;
     display: flex;
     justify-content: flex-end;
     align-items: center;
 }
  #nav #logo-url{
      margin: auto;
      margin-left: 0;
  }

  #logo{
      width: 139px;
      height: 46px;
  }
  #nav a{
      color: #fff;
      text-decoration: none;
      margin: 12px;
      transition: .5s;
  }
  #nav a:hover{
      color: #184e77;
      
  }
</style>
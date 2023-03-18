<template>
  <div class="main-home">

      <h2>Welcome</h2>

    <p>Welcome to AltSchool Africa Vue.js course final project.
      
      My name is Victor Akpu,
      I am a student of AltSchool Africa, Frontend track.
      
      Click on <router-link to="/about">About</router-link> to know about the
      project.</P>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>


<style>

h2 {
   text-align: center;
   margin-bottom: 50px;
    color:rgba(198,123,17,1);
}
.main-home{
  margin-top: 100px;
  text-align: center;
  /* width: 700px;  */
  
  
}
p{
  font-size: 20px;
  font-weight: bold;
  color:#660da2;
  padding-left: 20rem;
  padding-right: 20rem;

  
}
</style>
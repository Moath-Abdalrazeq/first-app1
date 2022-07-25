<script lang="ts">
import { defineComponent } from "vue";
import imagep from "../assets/flag.jpg"
 export default defineComponent({
  name: "ImagePalestine",
  components: {},


  setup() {



    return {imagep };
  },
});
</script>

<template>
 
    <div>
   <img :src="imagep" alt="" class="logo"/>
   <div class="div"> palestine flag </div>
    </div>
</template>

<style scoped>
 .logo {
    width:300px;
    height:200px;
 
 }

 .div{
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  font-size: 50px;
  font-style: italic;
  color:blue;
 }
  
 
</style>

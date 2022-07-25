<script lang="ts">
import { defineComponent } from "vue";
  
 import imagePalestine from "./image-palestine.vue"

 import threeButtons from "./three-buttons.vue"
export default defineComponent({
  name: "baseHeader",
  components: {imagePalestine ,threeButtons   },
  setup() {
    return {  };
  },
});
</script>
 
<template>
<three-buttons></three-buttons>
<image-palestine></image-palestine>
 </template>

<style scoped>


</style>

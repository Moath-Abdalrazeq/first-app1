<script lang="ts">
import { defineComponent } from "vue";
 
 export default defineComponent({
  name: "three-buttons",
  components: {},


  setup() {



    return {  };
  },
});
</script>

<template>
 
    <div>
    <button>Button1 </button>  
    <button>Button2 </button>
    <button>Button3 </button>
    <br/>
    <br/>
     </div>
</template>

<style scoped>
 button{
    border:solid 2px aqua;
       
      background-color: sienna;
      color: white;
      padding: 15px 32px;
      text-align: center;
      font-size: 16px;
 }
</style>

<script>
import {defineComponent} from "vue";

export default defineComponent({
  name: "ExampleComponent",
  data(){
    return{
      songs:["Toxicity", "Forest", "Colors"]
    }
  }

})

</script>

<template>
  <h1>My favourite songs 🎶🎶🎶</h1>
<ul>
  <li v-for="song in songs">{{song}}</li>
</ul>
</template>



<style scoped>

</style>
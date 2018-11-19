<template>
  <div id="app" >
    
     <div >
     
      
      <login/>
      

    </div>
     
    <div >
      
      
      <formulario/>

      
     
    </div>
  </div>
</template>

<script>

import login from './components/login.vue'
import formulario from './components/formulario.vue'
export default {
  name: 'app',
  components:{
    login, formulario,
  },
  data () {
    
    
    return {
      
    }
  }
}
</script>

<style>

</style>

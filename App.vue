<template>
  <div id="app" v-bind:style="{ backgroundColor: color}">
    
     <div >
       
      <formulario/>
      

     </div>
     
    <div >
      
      <login/>
      
     
    </div>
  </div>
</template>

<script>
import login from './components/login.vue'
import formulario from './components/formulario.vue'
export default {
  name: 'app',
  components:{
    login, formulario
  },
  data () {
    
    todos;[
          {nombre: 'nombre',apellido:'apellido',ciudad:'ciudad',sexo:'sexo',fecha:'fecha de nacimiento', direc:"direccion de entrega"}
      ]

    
    return {
      
    }
  }
}
</script>

<style>

</style>

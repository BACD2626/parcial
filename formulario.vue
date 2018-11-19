<template>
  <div>
      <h1>FORMULARIO DE ENTREGA</h1>
      <h3>nombre </h3>
    <input type=“text” placeholder='' name=“txtusuario” />
    <br>
    <br>
    <h3>apellido</h3>
    <input type=“text” placeholder='' name=“txtusuario” />
    <br>
    <br>
     <h3>ciudad</h3>
    <input type=“text” placeholder='' name=“txtusuario” />
    <br>
    <br>
     <h3>sexo</h3>
    <input type=“text” placeholder='' name=“txtusuario” />
    <br>
    <br>
     <h3>fecha de nacimiento</h3>
    <input type=“text” placeholder='' name=“txtusuario” />
    <br>
    <br>
     <h3>direccion de entrega</h3>
    <input type=“text” placeholder='' name=“txtusuario” />
    <br> <br>

    
<el-switch
  v-model="value6"
  disabled>
</el-switch>
<el-switch
  v-model="value7"
  disabled>
</el-switch>


    
           
  </div>
</template>

<script>
export default {
  name:'',
  data () {
    return {
      
    }
  }
}
</script>

<style>

</style>
 

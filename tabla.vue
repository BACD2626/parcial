<template>
  <div>
      
      
  </div>
</template>

<script>
vue.component('todo-item', {
props:['todo'],
template: `<li>{{todo.nombre}}<li>
`
})

import Vue from "vue";
vue.component('todo-list',{
props: ['todos'],
template: `
 <ul>
    <todo-item
        v-for="(todo,index) in todos"
        :todo="todo">
    </todo-item>
 </ul>
`

})
const app = new Vue({
    el: 'app',
    data: {
        todos:[
          {nombre: 'nombre',
          apellido:'apellido',
          ciudad:'ciudad',
          sexo:'sexo',
          fecha:'fecha de nacimiento',
          direc:'direccion de entrega'}
      ]
    },
    template: `
    <todo-list :todos="todos"></todo-list>
    `
})


</script>

<style>

</style>

      ]

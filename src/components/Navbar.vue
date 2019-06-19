<template>
  <div>
    <nav class="navbar navbar-light bg-light">
      <a class="navbar-brand">Busca tu Peli</a>
      <form class="form-inline" v-on:submit.prevent="search">
        <input v-model="tituloPeli" class="form-control mr-sm-2" type="search" placeholder="Buscar" aria-label="Search" v-on:keyup.enter="agregarAuto">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Buscar</button>
      </form>
    </nav>  
  </div>
</template>

<script>
import { METHODS } from 'http';
export default {
  name: 'Navbar',
  data(){
    return {
      tituloPeli: ''
    }
    
  }
  // method: {
  //   search(){
  //     this.
  //   }
  // }
}
</script>


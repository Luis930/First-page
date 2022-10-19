<template>
<div>
  <cabezera/>
  <buscador/>
  <principal/>
  <final/>
 </div>
</template>

<script>
import cabezera from '~/components/cabezera.vue'
import buscador from '../components/buscador.vue'
import principal from '../components/principal.vue'
import final from '../components/final.vue';


export default {
  components:{
    cabezera,
    buscador,
    principal,
    final
},
  name: 'IndexPage'
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
body{
  background-color: black;
}
</style>


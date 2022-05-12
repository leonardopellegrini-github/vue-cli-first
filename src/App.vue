<template>
  <div>
    <titoloFile />
    <jumbotronPrimo />
  </div>
</template>

<script>

import titoloFile from '@/components/TitleHero.vue'
import jumbotronPrimo from '@/components/JumbotronHero.vue'

export default {
  name: 'App',
  components: {
    titoloFile,
    jumbotronPrimo,
  }
}

</script>

<style>
body{
  background-color: black;
  color: white;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

h1{
  text-align: center;
}

.jumcar{
  height: 300px;
  background-color: green;
  color: white;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}



</style>

<template>
  <div>
    <titoloFile />
    <jumbotronPrimo />
  </div>
</template>

<script>

import titoloFile from '@/components/Title.vue'
import jumbotronPrimo from '@/components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    titoloFile,
    jumbotronPrimo,
  }
}

</script>

<style lang="scss">
  
</style>

<template>
  <div id="app">
    <!-- {{ message}} -->
    <element-view></element-view>
  </div>
</template>

<script>

import ElementView from './views/element/ElementView.vue'
export default {
  components: {ElementView},
  data: function(){
    return {
      message:"Hello Vue"
    }
  },
  method:{

  }
}
</script>

<style>

</style>
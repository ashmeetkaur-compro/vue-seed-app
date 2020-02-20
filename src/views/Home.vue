<template>
  <div class="home">
    <HelloWorld msg="Vue Seed App"/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import HelloWorld from '@/components/HelloWorld/HelloWorld.vue'

export default Vue.extend({
  name: 'Home',
  components: {
    HelloWorld
  }
})
</script>

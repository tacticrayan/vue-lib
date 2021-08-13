<template>
  <div class="box">
    <div>Mon nom est {{nom.first}} {{nom.last}}</div>
    <to-do></to-do>
  </div>
</template>

<script>
import ToDo from './ToDo.vue'
export default {
  components: {
    ToDo
  },
  props: ['nom'],
  mounted() {
     console.log('nom', this.nom)
  },
}
</script>

<style>
  .box {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
</style>
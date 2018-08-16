<template>
  
<!-- 2 inputai + mygtukas. ivedam img src ir title ir susikuria kortele -->
<!-- data() -->
<!-- methods: -->


  <div class="app container">
      <AppCard imageInside="http://kittytonpost.com/wp-content/uploads/2013/07/kittytonpost_wallpaper06.jpg" title="cat"/>
  </div>
</template>

<script>
import AppCard from './components/AppCard.vue'

export default {
  components: {
    AppCard
  },
  
  methods: {
    
  }
}
</script>

<style lang="scss" scoped>
  .app {
    padding-top: 50px;
  }
</style>



<!-- <p> {{ input }}</p> -->
      <!-- <button @click="addTodo">Prideti</button>
      <ul>
        <li v-for="(todo, index) in todos" :key="index">
          <s v-if="todo.done"> {{ todo.value}} </s>
          <template v-else>{{ todo.value }}</template>
          <button @click="setDoneTodo(index)"> X </button>
        </li>
      </ul> -->
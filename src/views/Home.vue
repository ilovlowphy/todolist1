<template>
  <div class="home">
    <AddTodo />
    <h1>This is Home page</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import AddTodo from '@/components/AddTodo.vue'

export default {
  name: 'Home',
  components: {
    AddTodo
  }
}
</script>

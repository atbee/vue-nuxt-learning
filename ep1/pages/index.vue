<template lang="html">
  <div>
    <ol>
      <TodoItem v-for="todo in todos" :key="todo.id" :item="todo"></TodoItem>
    </ol>
  </div>
</template>

<script>
import TodoItem from '@/components/TodoItem'
export default {
  components: {
    TodoItem
  },
  data() {
    return {
      todos: [
        { id: 1, text: 'hello vue' },
        { id: 2, text: 'hello react' },
        { id: 3, text: 'hello angular' }
      ]
    }
  }
}
</script>

<style></style>

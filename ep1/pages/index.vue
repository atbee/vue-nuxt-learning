<template>
  <div>
    <ol>
      <li v-for="(todo, index) in todos" :key="index">{{ todo.text }}</li>
    </ol>
  </div>
</template>

<script>
export default {
  data() {
    return {
      todos: [
        { text: 'Hello Vue' },
        { text: 'Hello React' },
        { text: 'Hello Angular' }
      ]
    }
  }
}
</script>

<style></style>

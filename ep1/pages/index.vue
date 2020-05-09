<template>
  <div>
    <span>{{ message }}</span>
    <button @click="reverseMessage">Reverse</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello Vue.js!'
    }
  },
  methods: {
    reverseMessage() {
      return (this.message = this.message
        .split('')
        .reverse()
        .join(''))
    }
  }
}
</script>

<style></style>

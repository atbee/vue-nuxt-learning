<template>
  <div>
    <span>{{ message }}</span>
    <br />
    <input type="text" v-model="message" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello Vue!'
    }
  }
}
</script>

<style></style>

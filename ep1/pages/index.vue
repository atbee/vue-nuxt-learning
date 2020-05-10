<template>
  <div>
    <span>{{ message }}</span>
    <br />
    <input type="number" v-model.number="message" />
    <p>{{ selected }}</p>
    <select v-model="selected">
      <option value="1">1</option>
      <option value="2">2</option>
    </select>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello Vue!',
      selected: null
    }
  }
}
</script>

<style></style>

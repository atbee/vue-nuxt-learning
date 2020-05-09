<template>
  <div>
    <span v-if="seen">Now you can see me</span>
  </div>
</template>

<script>
export default {
  data() {
    return {
      seen: false
    }
  }
}
</script>

<style></style>

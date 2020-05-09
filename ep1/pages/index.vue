<template>
  <div>
    <span v-if="seen">Now you can see me</span>
    <span v-else>You cannot see</span>
  </div>
</template>

<script>
export default {
  data() {
    return {
      seen: true
    }
  }
}
</script>

<style></style>

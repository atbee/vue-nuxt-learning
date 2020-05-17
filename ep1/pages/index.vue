<template>
  <div>
    <span :id="spanId">hello</span>
    <button :disabled="buttonDisabled">cannot click</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      spanId: 'hello',
      buttonDisabled: true
    }
  }
}
</script>

<style lang="scss" scoped></style>

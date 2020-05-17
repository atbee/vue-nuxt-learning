<template>
  <div>
    <span :id="spanId">hello</span>
    <button :disabled="buttonDisabled">cannot click</button>
    {{ 10 + 20 }}
    {{ 10 + 20 > 5 ? 'more than 5' : 'less than 5' }}
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

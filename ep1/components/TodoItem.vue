<template>
  <li>Please say {{ item.text }}</li>
</template>

<script>
export default {
  props: ['item'],
  mounted() {
    console.log(JSON.stringify(this.item))
  }
}
</script>

<style lang="css" scoped></style>

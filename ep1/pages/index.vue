<template>
  <div>
    <div v-html="rawHtml"></div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: 'Hello World!',
      rawHtml: '<h1>This is raw HTML</h1>'
    }
  }
}
</script>

<style lang="scss" scoped></style>

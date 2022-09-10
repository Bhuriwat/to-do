<template>
  <div>
    <h1>{{ title }}</h1>
    <h1>{{ likes }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    title: {
      type: String,
      required: true
    },
    likes: {
      type: Number,
      default: 1
    }
  }
}
</script>

<style lang="scss" scoped>

</style>

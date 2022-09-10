<template>
  <div>
    text here
    <v-text-field
      :value="data"
      @input="$emit('word',$event)"
    />
  </div>
</template>

<script>
export default {
  name: 'FormInput',
  props: {
    data: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="scss" scoped>

</style>

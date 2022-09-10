<template>
  <div>
    <FormInput
      @word="i = $event"
    />
    <h1>{{ i }}</h1>
    <CustomInput v-model="message" /> {{ message }}
  </div>
</template>

<script>
import FormInput from '~/components/FormInput.vue'

export default {
  name: 'CountNumber',
  components: { FormInput },
  data () {
    return {
      s: 0,
      i: 'fgslfg;lskjlck'
    }
  },
  methods: {
    increase () {
      this.s++
    },
    decrease () {
      this.s--
    },
    show (i) {
      this.i = i
    }
  }
}
</script>

<style lang="scss" scoped>

</style>

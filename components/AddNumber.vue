<template>
  <div>
    <button @click="$emit('increaseBy', 1)">
      Increase by 1
    </button>
  </div>
</template>

<script>
export default {
  name: 'IncreaseBy',
  data () {
    return {
      num: 0
    }
  }
}
</script>

  <style lang="scss" scoped>

  </style>

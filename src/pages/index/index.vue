<template>
  <view class="index">
    <text>{{ msg }}</text>
  </view>
</template>

<script>
import './index.scss'

export default {
  data () {
    return {
      msg: 'Hello world!'
    }
  }
}
</script>
<style scoped lang="scss">
.index {
  width: 7.5rem;
}
</style>

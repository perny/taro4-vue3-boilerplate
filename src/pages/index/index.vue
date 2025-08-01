<template>
  <view class="index">
    <Counter title="按钮1" />
  </view>
</template>

<script>
import './index.scss'
import Counter from '../../components/Counter.vue'

export default {
  name: 'IndexComp',
  components: {
    Counter
  }
}
</script>
<style scoped>

</style>

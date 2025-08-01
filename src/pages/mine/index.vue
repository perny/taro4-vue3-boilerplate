<template>
  <view class="index">
    <Counter title="按钮2" />
  </view>
</template>

<script>
import './index.scss'
import Counter from '../../components/Counter.vue'

export default {
  name: 'MineComp',
  components: {
    Counter
  }
}
</script>

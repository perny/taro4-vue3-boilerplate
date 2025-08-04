<template>
  <view class="index">
    <nut-cell title="我是标题" desc="描述文字" @click="click"></nut-cell>
    <nut-popup v-model:visible="show" closeable position="bottom" style="height: 50%;">
      这里是 popup 的内容
    </nut-popup>
    <Counter title="按钮1" />
    <Location2 color="#000000" />
  </view>
</template>

<script lang="ts" setup>
import { Location2 } from '@nutui/icons-vue-taro'
import './index.scss'
import Counter from '../../components/Counter.vue'
import { ref } from 'vue';

const show = ref(false)
const click = () => {
  show.value = true;
};
</script>
<style scoped>

</style>

<template>
  <view
    class="divider-box"
    :style="{ height: height, width: width, backgroundColor: bgColor }"
  ></view>
  <view class="">hah </view>
  <view>啊哈哈哈</view>
  <view class="">
  	kewu a 
  </view>
  <view>de </view>
</template>

<script>
export default {
  data() {
    return {};
  },
  props: {
    bgColor: {
      type: String,
      default: '#FBFBFB',
    },
    width: {
      type: String,
      default: '750rpx',
    },
    height: {
      type: String,
      default: '20rpx',
    },
  },
  methods: {},
};
</script>
<style lang="scss" scoped>
.divider-box {
  margin-left: -30rpx;
}
</style>

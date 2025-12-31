<script setup lang="ts">
// 业务逻辑后续补充
</script>

<template>
  <view class="container px-4 py-5">
    <!-- 生鲜商品卡片 -->
    <view class="bg-white rounded-lg shadow-sm mb-4 p-4">
      <!-- 商品图片 -->
      <image
        src="https://fastly.picsum.photos/id/903/200/200.jpg?hmac=lxHKyjlQqAkKyuVGkgUCO_jdWkg3osj3nTuULFHZxH8"
        class="w-full h-60 rounded-md object-cover mb-3"
        mode="aspectFill"
      ></image>
      <!-- 商品信息 -->
      <view class="flex justify-between items-start">
        <view class="flex-1">
          <text class="text-base font-medium text-gray-800">新鲜番茄 500g</text>
          <text class="block text-primary text-lg font-bold mt-2">¥3.99</text>
          <text class="text-sm text-gray-500 line-through">¥5.99</text>
        </view>
        <!-- 拼团按钮 -->
        <button class="bg-primary text-white px-4 py-2 rounded-full text-sm">
          发起拼团
        </button>
        <button>我是</button>
      </view>
    </view>
  </view>
</template>

<style scoped>
/* 无需手写大量样式，全部用Tailwind类名搞定 */
</style>

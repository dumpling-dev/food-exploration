<template>
	<img class="logo" src="@/static/hometop.png" />
	<view class="content">
		<view class="text-area">
			<text class="title">{{ title }}</text>
		</view>
	</view>
	<Home></Home>
</template>
	
<script setup>
import Home from '@/component/home.vue';
</script>

<style scoped>
.content {
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
}

.logo {
	width: 100%;
    
}

.text-area {
	display: flex;
	justify-content: center;
}

.title {
	font-size: 36rpx;
	color: #8f8f94;
}
</style>

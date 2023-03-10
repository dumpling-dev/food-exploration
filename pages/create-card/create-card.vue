<template>
	<div class="container">
		<div class="avatar">
			<fui-avatar text="刘" background="#FFB703"></fui-avatar>
			<fui-avatar text="刘" background="#FFB703"></fui-avatar>
		</div>
		<form action="#">
			<fui-input label="店铺名称" :bottomLeft="0" placeholder="请输入店铺名称"></fui-input>
			<fui-card :padding="['20rpx', '32rpx']" full :src="src" title="店铺地址" tag="额外信息">
				<!-- <view class="fui-card__content fui-padding">自定义内容区域</view> -->
			</fui-card>
			<div class="image-uploader">
				菜品图片上传
			</div>
			<fui-textarea placeholder="评论"></fui-textarea>
			<fui-radio-group name="radio" v-model="radioVal" @change="change">
				<view class="fui-list__item">
					<fui-label>
						<view class="fui-align__center">
							<fui-radio value="1" checked></fui-radio>
							<text class="fui-text">私密</text>
						</view>
					</fui-label>
					<fui-label>
						<view class="fui-align__center">
							<fui-radio value="2"></fui-radio>
							<text class="fui-text">公开</text>
						</view>
					</fui-label>
				</view>
			</fui-radio-group>
			<div class="btn">
				<fui-button width="350rpx" background="#fff" color="#465CFF" borderColor="#465CFF">发布</fui-button>
				<fui-button width="350rpx" background="#fff" color="#465CFF" borderColor="#465CFF">重置</fui-button>
			</div>
		</form>


	</div>
</template>

<script setup>
import { ref } from "vue"

const radioVal = ref(0)
</script>

<style>
.container {
	width: 100%;
	background-color: rgb(241, 244, 250);
}

.image-uploader {
	width: 200rpx;
	height: 200rpx;
	border: 5rpx solid rgb(112, 182, 255);
	border-radius: 20rpx;
	margin-top: 10rpx;
}

.fui-list__item {
	display: flex;

	/* justify-content: space-around; */
	background-color: white;
	margin-top: 5rpx;
	padding: 35rpx 20rpx;
}

.btn {
	/* width: 100%; */
	display: flex;
	justify-content: space-around;
	/* width: 300rpx; */
	margin-top: 10rpx;

}
</style>

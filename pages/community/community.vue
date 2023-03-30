<template>
	<div>
		<fui-radio-group name="radio" v-model="val" @change="change">
			<view class="fui-list__item">
				<fui-label>
					<view class="fui-align__center">
						<fui-radio value="1" checked></fui-radio>
						<text class="fui-text">个人</text>
					</view>
				</fui-label>
				<fui-label :margin="['0', '0', '0', '40rpx']">
					<view class="fui-align__center">
						<fui-radio value="2"></fui-radio>
						<text class="fui-text">共享社区</text>
					</view>
				</fui-label>
			</view>
		</fui-radio-group>
		<div class="frame">
			<div class="avatar">
				<fui-avatar text="刘" background="#FFB703"></fui-avatar>
			</div>

			<div class="content"> 发布的内容</div>
			<div class="bookmark">
				<div class="f_right">
					<span class="span">评论<fui-icon name="comment" :size="60"></fui-icon></span>
					<span class="span">收藏<fui-icon name="star" :size="60"></fui-icon></span>
					<span class="span">点赞<fui-icon name="fabulous" :size="60"></fui-icon></span>
				</div>
			</div>
		</div>

	</div>
</template>

<script setup>

</script>

<style scoped>
page {
	margin: 0;
	padding: 0;
}

.fui-list__item {
	display: flex;

	/* justify-content: space-around; */
	background-color: white;
	margin-top: 5rpx;
	padding: 35rpx 20rpx;
}

.frame {
	width: 90%;
	height: 250rpx;
	border: 1rpx solid #2a4474;
	margin: auto;
	display: flex;

	flex-wrap: wrap;

}

.avatar {
	width: 15%;
	height: 180rpx;
	/* background-color: rgb(88, 58, 58); */
	border: 1rpx solid #201314;
}

.content {
	width: 83%;
	height: 180rpx;
	/* background-color: rgb(48, 32, 32); */
	border: 1rpx solid #201314;
}

.bookmark {
	width: 100%;
}

.f_right {
	display: flex;
	justify-content: flex-end;
	margin-right: 10rpx;
}

.f_right .span {
	padding: 10rpx 10rpx;
}
</style>

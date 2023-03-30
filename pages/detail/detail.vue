<template>
	<div>
		<div class="picture">
		</div>
		<div class="data_detail">
			<div>店铺名称：</div>
			<div>店铺地址</div>
			<div>评分：</div>
		</div>
		<div class="reviews">
			评论
		</div>
		<ul class="reviews_list">
			<div class="li">
				<div class="avatar">
					<div class="avatar_img">
						头像
					</div>
				</div>
				<div class="my_view">
					<p>hyk</p>
				</div>
			</div>
			<!-- <div class="li"></div>
			<div class="li"></div>
			<div class="li"></div> -->
		</ul>
	</div>
</template>

<script setup>

</script>

<style scoped>
.picture {
	width: 90%;
	height: 300rpx;
	border: 1rpx solid #a3a2a2;
	margin: auto;
	margin-top: 60rpx;

}

.data_detail {
	width: 90%;
	height: 150rpx;
	border: 1rpx solid #a3a2a2;
	margin: auto;
}

.reviews {
	width: 90%;
	height: 50rpx;
	border: 1rpx solid #a3a2a2;
	margin: auto;
	margin-top: 30rpx;
	/* display: flex; */
}

.reviews_list>.li {
	width: 90%;
	height: 120rpx;
	border: 1rpx solid #a3a2a2;
	margin: auto;
	display: flex;
}
.avatar {
	width: 20%;
	height: 120rpx;
	border: 1rpx solid #a3a2a2;
	/* display: flex; */
	/* justify-content: space-around; */
}

.avatar_img {
	width: 60rpx;
	height: 60rpx;
	border: #201314 solid 1rpx;
	/* align-items: center; */

	margin: auto;
	margin-top: 20rpx;
	border-radius: 50%;
	text-align: center;
	line-height: 20rpx;
}
.my_view {
	width: 80%;
	height:120rpx;
	border: 1rpx solid #a3a2a2;
}
</style>


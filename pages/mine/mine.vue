<template>
	<div>
		<div class="box_header">
			<div class="avatar">
				<div class="avatar_img">
					头像
				</div>
			</div>
			<div class="my_name">
				<h3>name</h3>
				<p>hyk</p>
			</div>

		</div>
		<div class="box_session">

			<span class="span">关注</span>
			<span class="span">粉丝</span>
			<span class="span">获赞/收藏</span>
		</div>
		<div class="calendar">
		</div>
	</div>
</template>

<script setup>

</script>

<style scoped>
.box_header {
	width: 90%;
	height: 300rpx;
	border: 1rpx solid #a3a2a2;
	margin: auto;
	margin-top: 60rpx;
	display: flex;
}

.avatar {
	width: 30%;
	height: 300rpx;
	border: 1rpx solid #a3a2a2;
	/* display: flex; */
	/* justify-content: space-around; */
}

.avatar_img {
	width: 160rpx;
	height: 160rpx;
	border: #201314 solid 1rpx;
	/* align-items: center; */

	margin: auto;
	margin-top: 40rpx;
	border-radius: 50%;
	text-align: center;
	line-height: 160rpx;
}

.my_name {
	width: 70%;
	height: 300rpx;
	border: 1rpx solid #a3a2a2;
}

.box_session {
	width: 90%;
	height: 60rpx;
	border: 1rpx solid #a3a2a2;
	margin: auto;
	/* padding-left: 10rpx; */
}

.box_session>.span {
	margin-left: 15rpx;
	border: 1rpx solid #201314;
	border-radius: 80rpx;
}
.calendar{
	width: 90%;
	height: 560rpx;
	border: 1rpx solid #a3a2a2;
	margin: auto;
	margin-top: 60rpx;
}
</style>
         
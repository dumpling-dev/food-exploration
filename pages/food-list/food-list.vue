<template>
	<div class="contanier">
		<div class="foodlist_name">
			<text>美食榜单</text>
		</div>
		<div class="foodlist">
			<div class="list">
				<div class="list_left"></div>
				<div class="list_right"></div>
			</div>
		</div>
		<div class="foodlist">
			<div class="list">
				<div class="list_left"></div>
				<div class="list_right"></div>
			</div>
		</div>
		<div class="foodlist">
			<div class="list">
				<div class="list_left"></div>
				<div class="list_right"></div>
			</div>
		</div>
	</div>
</template>

<script setup>

</script>

<style scoped>
.contanier {
	width: 100%;
	background-color: rgb(211, 236, 236, 0.2);
}

.foodlist_name {
	width: 99%;
	height: 100rpx;
	border: 1rpx solid rgb(240, 237, 237);
	margin: auto;
	text-align: center;
	background-color: white;
	border-radius: 50rpx;
	box-shadow: 10rpx 10rpx 10rpx rgb(172, 172, 172, 0.3);
}

.foodlist_name>text {
	color: rgb(228, 197, 158);
	display: inline;
	line-height: 100rpx;
	font-size: larger;
}
.list{
	width: 90%;
	height: 250rpx;
	/* border: 1rpx solid rgb(113, 95, 95); */
	margin: auto;
	margin-top: 50rpx;
    display: flex;
}
.list_left{
   width: 80%;
   height: 250rpx;
   border: 1rpx solid rgb(224, 224, 224);
   background-color: white;
   border-radius: 20rpx;
   box-shadow: 10rpx 10rpx 10rpx rgb(172, 172, 172, 0.3);
}
.list_right{
	width: 20%;
   height: 150rpx;
   border: 1rpx solid rgb(206, 202, 202);
   /* line-height: 150rpx; */
   margin-top: 55rpx;
   border-radius: 20rpx;
   box-shadow: 10rpx 10rpx 10rpx rgb(172, 172, 172, 0.3);

}
</style>

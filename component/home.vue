<template>
    <div class="create-card">
        <span class="text_clr"> 创建打卡</span>
        <fui-icon name="plussign-fill"></fui-icon>
    </div>
    <div class="invitation-card">
        <span class="text_clr">邀请打卡</span>
        <fui-icon name="plussign-fill"></fui-icon>
    </div>
</template>
<script setup>
</script>
<style>
.create-card,
.invitation-card {
    width: 90%;
    height: 200rpx;
    border: 1rpx solid rgb(222, 230, 229);
    border-radius: 20rpx;
    box-shadow: 10rpx 10rpx 10rpx rgb(236, 237, 238);
    margin: auto;
    margin-top: 40rpx;
    display: flex;
    justify-content: space-between;

}

.text_clr {
    /* display: inline; */
    font-size: 30rpx;
    font-weight: 700;
    color: rgb(40, 39, 41);
    align-self: center;
    margin-left: 20rpx;
}

.create-card :nth-child(2),
.invitation-card :nth-child(2) {
    align-self: center;
    margin-right: 20rpx;
}
</style>
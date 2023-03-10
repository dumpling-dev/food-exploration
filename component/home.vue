<template>
    <div class="create-card">
        <span class="text_clr">创建打卡</span>
        <fui-icon name="plussign-fill" color="#465CFF"></fui-icon>
    </div>
    <div class="invitation-card">
        <span class="text_clr">邀请打卡</span>
        <fui-icon name="plussign-fill" color="#465CFF"></fui-icon>
    </div>
</template>
<script setup>
</script>
<style>
.create-card,
.invitation-card {
    width: 90%;
    height: 200rpx;
    border: 5rpx solid rgb(112, 182, 255);
    border-radius: 20rpx;
    /* background-color: rgb(112, 182, 255); */
    margin: auto;
    margin-top: 40rpx;
    display: flex;
    /* justify-content: center;  */
    justify-content: space-between;

}

.text_clr {
    display: inline;
    font-size: 60rpx;
    font-weight: 700;
    color: rgb(181, 114, 201);
    align-self: center;
    margin-left: 20rpx;
}

.create-card :nth-child(2),
.invitation-card :nth-child(2) {
    align-self: center;
    margin-right: 20rpx;
}
</style>
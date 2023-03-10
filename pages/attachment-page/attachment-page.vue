<template>
	<!--nvue端，超出一屏滚动时scroll和alignLeft必须同为true-->
	<fui-tabs  :tabs="tabs" isDot scroll></fui-tabs>
    <fui-input borderTop placeholder="搜索"></fui-input>

</template>

<script setup>
const tabs = [{
	name: '关注'
}, {
	name: '粉丝'
}]
</script>

<style></style>

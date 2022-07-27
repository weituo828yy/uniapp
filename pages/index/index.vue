<template>
	<view >
		<text>首页</text>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		//每次进入该页面均会触发
		onShow(){
			console.log('index onshow');
		},
		onLoad() {
			console.log(getCurrentPages());
		},
		//下来刷新触发
		onPullDownRefresh(){
			console.log('下拉刷新');
		},
		methods: {

		}
	}
</script>

<style>
</style>

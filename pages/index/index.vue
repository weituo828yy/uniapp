<template>
	<view >
		<u-button text="月落" type="primary" :plain="true"></u-button>
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

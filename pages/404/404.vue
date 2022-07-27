<template>
	<view>
		页面不存在！！！
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onLoad(){
			/**
			 * 2秒后跳转至首页
			 */
			let timer = setTimeout(()=>{
				clearTimeout(timer) //清除内存
				uni.reLaunch({
					url:'/pages/index/index'
				})
			},2000)
		},
		methods: {
			
		}
	}
</script>

<style>

</style>

<template>
	<view class="content ">
		<image class="logo" src="/static/logo.png"></image>
		<view class="text-area">
			<text class="title font_10">{{title}}</text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		//监听页面加载，参数为上个页面传递的数据，参数类型为Object
		onLoad() {

		},
		//监听页面显示，每次显示都会触发
		onShow() {
			
		},
		//页面初次渲染完成（如果页面过于简单，会渲染速度很快，也许会在页面进入动画完成之前触发）
		onReady() {
			
		},
		//监听页面隐藏
		onHide() {
			
		},
		//监听页面卸载
		onUnload() {
			
		},
		//监听用户下拉动作
		onPullDownRefresh() {
			
		},
		//页面滚动到底部，
		onReachBottom() {
			
		},
		//其他生命周期都有平台限制，有需要是去官网查询：https://uniapp.dcloud.io/collocation/frame/lifecycle?id=页面生命周期
		methods: {

		}
	}
</script>

<style lang="scss">
	 //scss  嵌套，变量，& 父级
	 $width : 200rpx ;
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		.logo {
			height: 200rpx;
			width: $width;
			margin-top: 200rpx;
			margin-left: auto;
			margin-right: auto;
			margin-bottom: 50rpx;
		}
		.text-area {
			display: flex;
			justify-content: center;
		}
		
		.title {
			font-size: 36rpx;
			color: #8f8f94;
			&.font_10{
				font-size: 100rpx;
				color: #007AFF;
			}
		}
	}

	

	
</style>

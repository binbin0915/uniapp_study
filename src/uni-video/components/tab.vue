<template>
	<view class="tab">
		<view class="tab-box">
			首页
		</view>
		<view class="tab-box">
			关注
		</view>
		<view class="tab-box">
			<view class="iconfont icon-21 icon-box">
			</view>
		</view>
		<view class="tab-box">
			消息
		</view>
		<view class="tab-box">
			我
		</view>
		
	</view>
</template>

<script>
</script>

<style>
	.tab{
		height: 50px;
		width: 100%;
		position: fixed;
		bottom: 0;
		left: 0;
	}
	.tab-box{
		float: left;
		width: 20%;
		color: #FFFFFF;
/* 		background-color:#000000; */
		height: 50px;
		line-height: 50px;
		text-align: center;
		font-size: 20px;
	}
	.icon-box{
		border-radius: 5px;
		width: 60%;
		height: 30px;
		background-color: #FFFFFF;
		color: #000000;
		margin: 10px 20%;
		line-height: 30px;
		font-size: 15px;
	}
</style>

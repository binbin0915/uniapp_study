<template>
	<view class="videoList">
		<view class="swiper-box">
			<swiper class="swiper" :vertical="true">
				<swiper-item v-for="item of videos" :key="item.id">
					<view class="swiper-item">
						<video-player :video="item"></video-player>
					</view>
					<view class="left-box">
						<list-left></list-left>
					</view>
				</swiper-item>
				
			</swiper>
		</view>
	</view>
</template>

<script>
	import videoPlayer from "./videoPlayer.vue"
	import listLeft from "./listLeft.vue"
	export default {
		props:['list'],
		components:{
			videoPlayer,
			listLeft
		},
		data(){
			return {
				videos:[
					// {
					// 	id:1,
					// 	src:require( "../static/video/1.mp4")
					// },
					// {
					// 	id:2,
					// 	src:require( "../static/video/2.mp4")
					// },
					// {
					// 	id:3,
					// 	src:require( "../static/video/3.mp4")
					// },
					// {
					// 	id:4,
					// 	src:require( "../static/video/4.mp4")
					// },
				]
			};
		},
		watch:{
			list(){
				this.videos = this.list;
			}
		}
	}
</script>

<style>
	
	.videoList{
		height: 100%;
		width: 100%;
	}
	
	.swiper-box{
		height: 100%;
		width: 100%;
	}
	 
	.swiper{
		height: 100%;
		width: 750rpx;
	}
	
	.swiper-item{
		height: 100%;
		width: 100%;
		z-index: 19;
	} 
	
	.left-box{
		z-index: 20;
		position: absolute;
		bottom: 80px;
		left: 10px;
	}
</style>

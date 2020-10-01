<template>
	<view class="videoPlayer">
		<video  class="video" :controls="false" :loop="true" :src="video.src" controls="true" autoplay="true"></video>
		<!-- <view style="background-color:#4CD964;" class="video">{{video.id}}---{{video.author}}</view> -->
	</view>
</template>

<script>
	export default{
		props:['video'],
		data(){
			return {
				
			}
		},
		watch:{
			video(){
				console.log(this.video);
			}
		}
	}
</script>

<style>
	.videoPlayer{
		width: 100%;
		height: 100%;
	}
	
	.video{
		width: 100%;
		height: 100%;
	}
</style>

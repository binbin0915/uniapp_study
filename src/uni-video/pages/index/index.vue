<template>
	<view class="content">
		<first-nav></first-nav>
		<video-list :list="list"></video-list>
		<tab></tab>
	</view>
</template>

<script>
	import tab from "../../components/tab.vue"
	import firstNav from "../../components/first-nav.vue"
	import videoList from "../../components/videoList.vue"
	export default {
		components:{
			tab,
			firstNav,
			videoList
		},
		data() {
			return {
				list: []
			}
		},
		onLoad() {
			this.getVideos();
		},
		methods: {
			getVideos(){
				uni.request({
					url:"http://192.168.1.38:14281/api/video.json",
					success:(res)=>{
						
						this.list = res.data.list;
						console.log(this.list);
					}
				})
			}
		}
	}
</script>

<style>
	.content {
		height: 100%;
		width: 100%;
	}


</style>

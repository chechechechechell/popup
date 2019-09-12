<template>
	<view class="content" v-show="isShow">
		<view class="cover" v-show="isShowCover">
			<view class="popupBody">
				<view>66666</view>
				<view>真的额</view>
			</view>
			
		</view>

	</view>
</template>

<script>
	export default {
		data() {
			return {
				isShow:true,
				isShowCover:true
				
				
			};
		}
	}
</script>

<style lang="scss">
	.content {
		height: 100vh;
		width: 100vh;
		.cover {
			position: fixed;
			top: 0;
			left: 0;
			background-color: rgba(0, 0, 0, 0.6);
			height: 100%;
			width: 100%;
			.popupBody{
				background-color: rgba(255, 255, 255, 1);
				margin: 70% auto 0;
				padding: 20upx;
				width: 50%
			}
		}
	}

	
</style>

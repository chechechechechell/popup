<template>
	<view class="content" v-show="isShow">
		<view class="cover" v-show="isShowCover">
			
			
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
		height: 100%;
		width: 100%;
		.cover {
			background-color: rgba(0, 0, 0, 0.8);
			height: 100%;
			width: 100%;
		}
	}

	
</style>

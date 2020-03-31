<template>
	<view class="welcome-container">
		<image class="head-pic" src="../../static/avatar/4.png" mode=""></image>
		<text class="user-name">olin</text>
		<view class="in-btn">
			<text>进入豆瓣电影</text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		methods: {

		}
	}
</script>

<style scoped>
	.welcome-container {
		display: flex;
		flex-direction: column;
		align-items: center;
	}
	.head-pic{
		width: 154rpx;
		height: 154rpx;
		margin-top: 208rpx;
	}
	.user-name{
		font-size: 40rpx;
		font-weight: 600;
		color: #42bd56;
		margin-top: 108rpx;
	}
	.in-btn{
		font-size: 28rpx;
		color: #42bd56;
		margin-top: 204rpx;
		width: 204rpx;
		height: 88rpx;
		border-radius: 10rpx;
		border: #42BD56 solid 1rpx;
		display: flex;
		justify-content: center;
		align-items: center;
	}

</style>

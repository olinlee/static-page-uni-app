<template>
	<view>
		<view class="header">
			<view class="header-bg-blur" :style="{backgroundImage:`url(../../static/movies/p2411665175.jpg)`}">
			</view>
			<view class="header-info">
				<image src="../../static/movies/p2411665175.jpg" mode=""></image>
				<view class="header-title">
					<text>天空之眼</text>
					<view class="header-grade">
						<text>9.9</text>
						<view class="header-stars">
							<view>
								<image src="../../static/icon/star_1.png" mode=""></image>
								<image src="../../static/icon/star_1.png" mode=""></image>
								<image src="../../static/icon/star_1.png" mode=""></image>
								<image src="../../static/icon/star_1.png" mode=""></image>
								<image src="../../static/icon/star_1.png" mode=""></image>
							</view>
							<text class="totalParticipation">44444人评价</text>
						</view>
					</view>
				</view>
			</view>
		</view>
		<view class="info">
			<view class="info-content">
				<text>100分钟 喜剧、动作、冒险</text>
				<text>2017 中国大陆</text>
				<text>成龙 / 李治廷 / 张艺兴 / 索鲁·苏德</text>
			</view>
			<view class="btns">
				<view class="want-btn">
					<text>想看</text> 
				</view>
				<view class="seen-btn">
					<text>看过</text>
				</view>
			</view>
			<view class="synopsis">
				<text class="synopsis-title">剧情简介</text>
				<text class="synopsis-content">影片讲述了一名军事情报官为追捕一名恐怖分子，而在一次指挥无人机轰炸任务的战略决策过程中陷入两难境地的故事。英国伦敦联合司令部科洛内尔·凯瑟琳·鲍威尔上校（海伦·米伦 饰），奉命率领英国军事情报部门追捕一名位列反恐名单的恐怖组织分子长达六年，经由与美国内华达州克里奇空军基地的军用无人机小组联手加入的高空监视行动，终于在肯尼亚首都内罗毕境内的秘密基地发现了该名恐怖主义分子的身影。当鲍威尔通过高空侦查人员意外了解得知该恐怖组织正在密谋一场自杀性炸弹恐怖袭击计划时，为减轻伤亡的她当机立断地决定下令轰炸秘密基地将敌人歼灭。然而，正当无人战斗机驾驶员史蒂夫·沃茨（亚伦·保尔 饰）准备瞄准目标捣毁恐怖分子窝点时，他却发现这间看似秘密基地的房屋竟然是一间普通民居，而一名9岁女孩更跑进了他的射杀攻击范围内玩耍，原本单纯的跨国逮捕行动瞬间演变成了一场复杂难解的反恐任务。鲍威尔不得不联系律师和政府官员，决定是否继续执行此次任务……</text>
			</view>
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

<style>
	/* synopsis */
	.synopsis {
		width: 690rpx;
		display: flex;
		flex-direction: column;
		margin-top: 80rpx;
		font-size: 26rpx;
	}
	.synopsis-title {
		color: #dfe4e3;
		margin-bottom: 60rpx;
	}
	.synopsis-content {
		color: #2e2f2c;
	}

	/* btn */
	.btns {
		width: 690rpx;
		display: flex;
		justify-content: space-between;
		margin-top: 60rpx;
	}

	.btns>view {
		width: 324rpx;
		height: 66rpx;
		color: #e5aa70;
		font-size: 28rpx;
		border: #e5aa70 2px solid;
		border-radius: 15rpx;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	/* info */
	.info {
		width: 750rpx;
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.info-content {
		font-size: 24rpx;
		color: #3f3f3f;
		display: flex;
		flex-direction: column;
		margin-top: 60rpx;
		width: 690rpx;
	}

	.info-content>text {
		margin-top: 38rpx;
	}

	.info-content>text:first-child {
		margin-top: 0rpx;
	}


	/* header */
	.header {
		width: 750rpx;
		height: 396rpx;
		position: relative;
	}

	.header-bg-blur {
		width: 750rpx;
		height: 360rpx;
		background-size: 800rpx 1120rpx;
		background-position: -25rpx -380rpx;
		-webkit-filter: blur(10rpx);
		-moz-filter: blur(10rpx);
		-o-filter: blur(10rpx);
		-ms-filter: blur(10rpx);
		filter: blur(10rpx);
		position: absolute;
		left: 0rpx;
		top: 0rpx;
	}

	.header-info {
		width: 750rpx;
		height: 396rpx;
		position: absolute;
		left: 0rpx;
		top: 0rpx;
	}

	.header-info>image {
		width: 200rpx;
		height: 280rpx;
		position: absolute;
		left: 30rpx;
		top: 116rpx;
	}

	.header-title {
		display: flex;
		flex-direction: column;
		position: absolute;
		left: 260rpx;
		top: 160rpx;
		color: white;
		font-size: 40rpx;
	}

	.header-grade {
		margin-top: 50rpx;
		display: flex;
		align-items: center;
	}

	.header-stars {
		margin-left: 30rpx;
		display: flex;
		flex-direction: column;
		font-size: 22rpx;
	}

	.header-stars>view {
		margin-bottom: 16rpx;
	}

	.header-stars image {
		width: 16rpx;
		height: 16rpx;
	}
</style>

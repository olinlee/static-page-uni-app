<template>
	<view class="movies-container">
		<view class="search-box">
			<image src="../../static/icon/search.png" mode=""></image>
			<input type="text" value="" placeholder="请输入需要查询的电影" />
		</view>
		<view class="swiper-box">
			<swiper class="swiper" :indicator-dots="indicatorDots" :autoplay="autoplay" :interval="interval" :duration="duration">
				<swiper-item v-for="(swiperMovie,index) of swiperMovies" :key="index">
					<view class="swiper-item" :style="{backgroundImage: `url(${swiperMovie});`}"></view>
				</swiper-item>
			</swiper>
		</view>
		<view class="movies-box">
			<view class="moviesListTitle">
				<text>正在上映的电影</text>
				<view class="more">
					<text>更多</text>
					<image src="../../static/icon/arrow-right.png" mode=""></image>
				</view>
			</view>
			<view class="moviesList">
				<view class="movieItem">
					<image src="../../static/movies/p2411665175.jpg" mode=""></image>
					<text>天空之眼</text>
					<view class="stars">
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<text>9.9</text>
					</view>
				</view>
				<view class="movieItem">
					<image src="../../static/movies/p2411665175.jpg" mode=""></image>
					<text>天空之眼</text>
					<view class="stars">
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<text>9.9</text>
					</view>
				</view>
				<view class="movieItem">
					<image src="../../static/movies/p2411665175.jpg" mode=""></image>
					<text>天空之眼</text>
					<view class="stars">
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<text>9.9</text>
					</view>
				</view>
			</view>
		</view>
		<view class="movies-box">
			<view class="moviesListTitle">
				<text>正在上映的电影</text>
				<view class="more">
					<text>更多</text>
					<image src="../../static/icon/arrow-right.png" mode=""></image>
				</view>
			</view>
			<view class="moviesList">
				<view class="movieItem">
					<image src="../../static/movies/p2411665175.jpg" mode=""></image>
					<text>天空之眼</text>
					<view class="stars">
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<text>9.9</text>
					</view>
				</view>
				<view class="movieItem">
					<image src="../../static/movies/p2411665175.jpg" mode=""></image>
					<text>天空之眼</text>
					<view class="stars">
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<text>9.9</text>
					</view>
				</view>
				<view class="movieItem">
					<image src="../../static/movies/p2411665175.jpg" mode=""></image>
					<text>天空之眼</text>
					<view class="stars">
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<text>9.9</text>
					</view>
				</view>
			</view>
		</view>
		<view class="movies-box">
			<view class="moviesListTitle">
				<text>正在上映的电影</text>
				<view class="more">
					<text>更多</text>
					<image src="../../static/icon/arrow-right.png" mode=""></image>
				</view>
			</view>
			<view class="moviesList">
				<view class="movieItem">
					<image src="../../static/movies/p2411665175.jpg" mode=""></image>
					<text>天空之眼</text>
					<view class="stars">
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<text>9.9</text>
					</view>
				</view>
				<view class="movieItem">
					<image src="../../static/movies/p2411665175.jpg" mode=""></image>
					<text>天空之眼</text>
					<view class="stars">
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<text>9.9</text>
					</view>
				</view>
				<view class="movieItem">
					<image src="../../static/movies/p2411665175.jpg" mode=""></image>
					<text>天空之眼</text>
					<view class="stars">
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<image src="../../static/icon/star_1.png" mode=""></image>
						<text>9.9</text>
					</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				background: ['color1', 'color2', 'color3'],
				indicatorDots: true,
				autoplay: true,
				interval: 2000,
				duration: 500,
				swiperMovies: [
					"../../static/swiper/pos1.jpeg",
					"../../static/swiper/pos2.jpeg",
					"../../static/swiper/pos3.jpeg",
					"../../static/swiper/pos4.jpg",
				]
			}
		},
		methods: {

		}
	}
</script>

<style scoped>
	/* movieItem */
	.moviesList{
		display: flex;
		width: 682rpx;
		justify-content: space-between;
	}
	.movieItem {
		width: 200rpx;
		display: flex;
		flex-direction: column;
		font-size: 28rpx;
	}

	.movieItem>image {
		width: 200rpx;
		height: 270rpx;
		margin-bottom: 24rpx;
	}

	.stars {
		display: flex;
		align-items: center;
		margin-top: 22rpx;
	}

	.stars>image {
		width: 16rpx;
		height: 16rpx;
		margin-right: 4rpx;
	}

	.stars>text {
		font-size: 22rpx;
		margin-left: 10rpx;
	}

	/* moviesList */
	.moviesListTitle {
		width: 682rpx;
		display: flex;
		justify-content: space-between;
		font-size: 28rpx;
		margin: 34rpx 0rpx;
	}

	.moviesListTitle>text {
		color: #00084e;
	}

	.more>image {
		width: 20rpx;
		height: 20rpx;
	}

	.more>text {
		color: #36496c;
		margin-right: 5rpx;
	}

	/* swiper */
	.swiper {
		width: 682rpx;
		height: 400rpx;
	}

	.swiper-item {
		height: 400rpx;
		background-size: 682rpx 400rpx;

	}

	/* search */
	.movies-container {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	.search-box {
		display: flex;
		align-items: center;
		width: 750rpx;
		height: 80rpx;
		background-color: #f2f2f2;
	}

	.search-box>image {
		width: 32rpx;
		height: 32rpx;
		margin-left: 30rpx;
	}

	.search-box>input {
		margin-left: 30rpx;
		width: 600rpx;
		height: 80rpx;
	}
</style>

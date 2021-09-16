<template>
	<view class="content">
		<image class="logo" src="/static/fx67ll.png"></image>
		<view class="text-area"><text class="title">一些记录</text></view>
		<view class="text-line"></view>
		<view class="text-record">20210823，第一次联系她</view>
		<view class="text-line"></view>
		<view class="text-record">20210905，第一次吃饭，本来约了一个港茶，但是觉得人太多而且很吵，临时换了旁边的一个店，是一个藏式菜系的店，她说不好吃回去甚至想吐</view>
		<view class="text-line"></view>
		<view class="text-record">20210912，去了新开的吾悦广场吃了一家日料，她觉得还不错，她喝奶茶不喜欢放西米和西柚，吃日料店的时候不吃北极贝</view>
		<view class="text-record">
			吃完去看了失控玩家，小贱贱和杀死奶芙女猪脚演的那个电影，她说对于电影她很少关注剧情，只是当做娱乐活动罢了，她说之前下班就去剧本杀，社交的太狠了所以最近就很少出去，周末躺家里一天出去玩一天正正好
		</view>
	</view>
</template>

<script>
export default {
	data() {
		return {};
	},
	onLoad() {},
	methods: {}
};
</script>

<style lang="scss">
.content {
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
}

.logo {
	height: 200rpx;
	width: 200rpx;
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
}

.text-record {
	margin: 0 auto;
	margin-top: 10px;
	padding: 20px;
	display: flex;
	justify-content: center;
	text-align: center;
	font-size: 36rpx;
	color: #8f8f94;
}

.text-line {
	width: 100%;
	border-top: 2px dashed #8f8f94;
	margin-top: 10px;
}
</style>

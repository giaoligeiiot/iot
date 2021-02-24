<template>
	<view>
		<u-search style='margin:30rpx' placeholder="hii"></u-search>
		<banner />
		<view class='rec-goods-list flex'>
			<view class='item flex flex-col' v-for="item in 10">
				<image src="https://img.alicdn.com/bao/uploaded/i1/2207248684558/O1CN01PjrzyZ1jXbtuvSTw8_!!0-item_pic.jpg_468x468q75.jpg_.webp"
				 mode=""></image>
				<view class="goods-name"> </view>
				<view class="goods-price"> </view>
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
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang='scss'>
	.rec-goods-list {
		.item {
			&:active {
				box-shadow: 0 0 4rpx #aa0000;
			}

			box-shadow:0 0 2rpx #0000ff;
			width:100%;
			padding:20rpx;

			image {
				width: 90%;
				height: 360rpx;
			}

			.goods-name {
				font-weight: bold;
			}

			.goods-price {
				color: $my-color;
				font-weight: bold;
			}
		}
	}
</style>

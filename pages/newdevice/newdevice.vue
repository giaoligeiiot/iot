<template>
	<view>
		<view class="newdeviceImages">
				<view class="sbname">
					设备名称
				</view>
				<u-input class="value" :type="type" :border="border" :height="height" :auto-height="autoHeight" />
				<view class="sbm">
					设备码
				</view>
				<u-input class="value" :type="type" :border="border" :height="height" :auto-height="autoHeight" />
		</view>
		
		<view class="newdeviceAn">
			<u-button :ripple="true" ripple-bg-color="#00ff7f" type="success" size="medium">保存设备</u-button>
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
	.newdeviceAn {
		text-align: center;
	}
	.value{
		background-color: #ffffff;
		height: 70rpx;
		width: 100%;
		}
		.sbname{
			
		}
		.sbm{
			
		}
</style>

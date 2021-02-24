<template>
	<view class="wrap">
		<u-swiper :list="list"></u-swiper>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				list: [{
						image: 'https://bpic.588ku.com/art_water_pic/21/02/02/4fdece009bb99a0068389ae43bac71ee.jpg',
						title: '昨夜星辰昨夜风，画楼西畔桂堂东'
					},
					{
						image: 'https://bpic.588ku.com/art_water_pic/21/02/02/5a47f51c3637b2c4ac61562d946f1214.jpg',
						title: '身无彩凤双飞翼，心有灵犀一点通'
					},
					{
						image: 'https://bpic.588ku.com/art_water_pic/21/02/02/325a673f784cfd927a4fe326b75899d5.jpg',
						title: '谁念西风独自凉，萧萧黄叶闭疏窗，沉思往事立残阳'
					}
				],
			}
		},
		methods: {

		}
	}
</script>

<style lang="scss" scoped>
	.wrap {
		padding: 10rpx;
	}
</style>
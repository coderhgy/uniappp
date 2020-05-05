<template>
	<view class="p-2">
		<block v-for="(item,index) in list" :key="index">
			<view class="mb-2 p-2 line-h d-flex flex-column rounded bg-white">
				<view class="font-md text-dark">{{item.title}}</view>
				<text class="line-h-md text-light-muted">{{item.desc}}</text>
				<text class="line-h-md text-light-muted">{{item.time}}</text>
			</view>
		</block>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				list:[
					{
						title:"uni-appDemo",
						desc:"非常牛逼",
						time:"5月28"
					},
					{
						title:"uni-appDemo",
						desc:"非常牛逼",
						time:"5月28"
					}
				]
			}
		},
		methods: {
			
		}
	}
</script>

<style>
page{ background: #EEEEEE; }
</style>

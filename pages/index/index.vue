<template>
	<div>
		<div class="main-container">
			<div class="main-item item1">元素1</div>
			<div class="main-item item2">元素2</div>
			<div class="main-item item3">元素3</div>
		</div>
	</div>
</template>

<style>
	.main-container {
		width: 750rpx;
		height: 750rpx;
		background-color: #007AFF;
		display: flex;
		flex-flow: row nowrap;
		justify-content: center;
		align-items: baseline;
	}
	
	.main-item {
		width: 120px;
		height: 80px;
	}
	
	.item1 {
		background-color: #DD524D;
		padding-top: 20px;
		order: 1;
		flex-shrink: 0;
	}
	
	.item2  {
		background-color: #4CD964;
		height: 120px;
		order: 3;
		flex-shrink: 1;
	}
	
	.item3 {
		background-color: #F0AD4E;
		order: 2;
		align-self: flex-end;
		flex-shrink: 2;
	}
	
	.item4 {
		background-color: #C0C0C0;
	}
	
</style>

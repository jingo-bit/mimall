<template>
	<div class="tabbar">
		<div class="left">
			<li>松果出行</li>
			<li>MIMU</li>
			<li>云服务</li>
		</div>
		<div class="right">
			<li>登陆</li>
			<li>注册</li>
			<button class="add-shopping-btn">添加购物车</button>
		</div>

	</div>
</template>

<script>
	export default {
		name: 'Tabbar'
	}
</script>

<style scoped="scoped">
	.tabbar {
		width: 100%;
		background: rgba(51, 51, 51, 1);
		margin: auto;
		display: flex;
		justify-content: space-between;
		align-content: center;
		padding: 0 22px;
	}

	.left,
	.right {
		display: flex;
		/* padding: 10px; */
	}

	.left li,
	.right li {
		font-size: 12px;
		margin: 0 10px;
		color: #B0B0B0;
		line-height: 30px;
	}

	.left li:hover,
	.right li:hover {
		color: aquamarine;
		cursor: pointer;
	}

	.add-shopping-btn {
		background: rgba(102, 102, 102, 1);
		display: inline-block;
		height: 30px;
		width: 110px;
		text-align: center;
		line-height: 30px;
		border: none;
		
	}
	.add-shopping-btn:hover{
		background: #000000;
		color: #FFFFFF;
	}
</style>

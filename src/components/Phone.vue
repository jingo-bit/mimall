<template>
	<div class="content-fill">
		<h1>手机</h1>
		<div class="content">

			<div class="left-img">
				<img src="../assets/img/mix-alpha.jpg" alt="xx">
			</div>
			<div class="category">
				<div class="c-list">
					<img src="../assets/img/nav-img/nav-1.png" alt="">
					<div class="title"><span>小米9 6GB+128GB</span></div>
					<div class="child-title"><span>骁龙855，索尼4800万超广角微距</span></div>
					<p class="price">2999元</p>
				</div>
				<div class="c-list">
					<img src="../assets/img/nav-img/nav-1.png" alt="">
					<div class="title"><span>小米9 6GB+128GB</span></div>
					<div class="child-title"><span>骁龙855，索尼4800万超广角微距</span></div>
					<p class="price">2999元</p>
				</div>
				<div class="c-list">
					<img src="../assets/img/nav-img/nav-1.png" alt="">
					<div class="title"><span>小米9 6GB+128GB</span></div>
					<div class="child-title"><span>骁龙855，索尼4800万超广角微距</span></div>
					<p class="price">2999元</p>
				</div>
				<div class="c-list">
					<img src="../assets/img/nav-img/nav-1.png" alt="">
					<div class="title"><span>小米9 6GB+128GB</span></div>
					<div class="child-title"><span>骁龙855，索尼4800万超广角微距</span></div>
					<p class="price">2999元</p>
				</div>
				<div class="c-list">
					<img src="../assets/img/nav-img/nav-1.png" alt="">
					<div class="title"><span>小米9 6GB+128GB</span></div>
					<div class="child-title"><span>骁龙855，索尼4800万超广角微距</span></div>
					<p class="price">2999元</p>
				</div>
				<div class="c-list">
					<img src="../assets/img/nav-img/nav-1.png" alt="">
					<div class="title"><span>小米9 6GB+128GB</span></div>
					<div class="child-title"><span>骁龙855，索尼4800万超广角微距</span></div>
					<p class="price">2999元</p>
				</div>
				<div class="c-list">
					<img src="../assets/img/nav-img/nav-1.png" alt="">
					<div class="title"><span>小米9 6GB+128GB</span></div>
					<div class="child-title"><span>骁龙855，索尼4800万超广角微距</span></div>
					<p class="price">2999元</p>
				</div>
				<div class="c-list">
					<img src="../assets/img/nav-img/nav-1.png" alt="">
					<div class="title"><span>小米9 6GB+128GB</span></div>
					<div class="child-title"><span>骁龙855，索尼4800万超广角微距</span></div>
					<p class="price">2999元</p>
				</div>
			</div>
		</div>
	</div>


</template>

<script>
	export default {
		name: 'Phone'
	}
</script>

<style>
	.content-fill {
		width: 100%;
		margin: 20px;
		padding: 20px;
		background: rgba(245, 245, 245, 1);

	}

	.content {
		width: 100%;
		display: flex;
	}

	.content-fill h1 {
		font-size: 22px;
		font-family: FZLTHJW--GB1-0;
		margin: 15px 0;
	}

	.left-img {
		flex: 20%;
	}

	.left-img img {
		width: 100%;
	}

	.category {
		flex: 80%;
		display: flex;
		flex-wrap: wrap;
		overflow: hidden;
		margin-top: -20px;
	}
	.category .c-list{
		position: relative;
		box-sizing: border-box;
		flex: 20%;
		height: 44%;
		background: #fff;
		margin: 20px;
		transition: .8s linear;
		overflow: hidden;
	}
	.c-list::before{
		content: "热销";
		position: absolute;
		left: 50%;
		transform: translateX(-350%);
		/* transform: translateY(-50px); */
		transition: .8s linear;
		width: 50px;
		height: 20px;
		text-align: center;
		background: #7ECF68;
		color: white;
		
	}
	.c-list img{
		width: 190px;
		margin-top: 30px;
		transition: .4s;
	}
	.c-list:hover{
		cursor: pointer;
		transform: scale(1.09);
		
	}
	.c-list:hover .price{
		font-size: 20px;
	}
	.c-list:hover::before{
		transform: translateX(-50%);
	}
	.c-list .title{
		margin-top: 10px;
		text-align: center;
		font-size: 14px;
	}
	.c-list .child-title{
		font-size: 12px;
		text-align: center;
		color: #999999;
		padding: 5px 5px;
	}
	.price{
		text-align: center;
		color: #FF0000;
		transition: .8s;
	}
</style>

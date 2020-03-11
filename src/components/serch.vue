<template>
	<div class="serch">
		<img src="../assets/img/logo-footer.png" alt="">
		<div class="serch-center">
			<span><a href="#">小米手机</a></span>
			<span><a href="#">Redmi手机</a></span>
			<span><a href="#">电视</a></span>
		</div>
		<form action="#" class="serch-right">
			<input type="search" class="serch-box" placeholder="红米9">
			<a href="#">
				<i class="fas fa-search"></i>
			</a>
		</form>
	</div>
</template>

<script>
	export default{
		name:'Serch'
	}
</script>

<style scoped="scoped">
	@import url("../assets/fontawesome/css/all.css");
	.serch{
		width: 100%;
		height: 60px;
		background:rgba(255,255,255,1);
		padding: 0 22px;
		display: flex;
		align-content: center;
		position: relative;
	}
	.serch img{
		/* width: 33px; */
		height: 30px;
		position: absolute;
		top: 50%;
		left: 30px;
		transform: translateY(-50%);
	}
	.serch .serch-center{
		margin-left: 150px;
	}
	.serch .serch-center a{
		color: black;
	}
	.serch-center span{
		padding: 10px 10px;
		line-height: 60px;
	}
	.serch-center a:hover{
		color: red;
		cursor: pointer;
	}
	.serch-right{
		width: 200px;
		/* height: 40px; */
		/* background: red; */
		position: absolute;
		right: 22px;
		top: 50%;
		transform: translateY(-50%);
		border:1px solid rgba(224,224,224,1);
		/* padding: 0 8px; */
		text-indent: 2;
		padding-left: 10px;
		box-sizing: border-box;
	}
	.serch-box{
		border: none;
		outline: none;
		margin-right: 20px;
	}
	.fa-search:hover{
		color: #FF0000;
	}
</style>

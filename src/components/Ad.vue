<template>
	<div>
		<div class="ad-container">
			<div class='ad'>
				<img src="../assets/img/ads/ads-1.png" alt="xx">
			</div>
			<div class='ad'>
				<img src="../assets/img/ads/ads-2.jpg" alt="xx">
			</div>
			<div class='ad'>
				<img src="../assets/img/ads/ads-3.png" alt="xx">
			</div>
			<div class='ad'>
				<img src="../assets/img/ads/ads-4.jpg" alt="xx">
			</div>
		</div>
		<div class="banner">
			<img src="../assets/img/banner-1.png" alt="xx">
		</div>
	</div>

</template>


<script>
	export default {
		name: 'Ad',

	}
</script>

<style scoped="scoped">
	@import url("../assets/css/index.css");

	.ad-container {
		width: 100%;
		height: 167px;
		padding: 0 22px;
		display: flex;
	}

	.ad-container .ad {
		flex: 25%;
		padding: 10px 10px;
		overflow: hidden;

	}

	.ad-container img {
		width: 100%;
		height: 100%;
		cursor: pointer;
		transition: .4s linear;
	}

	.ad-container img:hover {
		transform: scale(1.3) rotate(15deg);
	}
	.banner{
		padding: 20px 22px;
		width: 100%;
		margin: auto;
	}
</style>

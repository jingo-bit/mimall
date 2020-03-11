<template>
	<div class="container">
		<div class="swiper-box">
			<swiper :options="swiperOption">
				<!-- slides -->
				<swiper-slide><img src="../assets/img/slide-1.jpg" alt="error"></swiper-slide>
				<swiper-slide><img src="../assets/img/slide-2.jpg" alt="error"></swiper-slide>
				<swiper-slide><img src="../assets/img/slide-3.jpg" alt="error"></swiper-slide>
				<swiper-slide><img src="../assets/img/slide-4.jpg" alt="error"></swiper-slide>
				<swiper-slide><img src="../assets/img/slide-5.jpg" alt="error"></swiper-slide>
				<!-- Optional controls -->
				<div class="swiper-pagination" slot="pagination"></div>
	<!-- 			<div class="swiper-button-prev" slot="button-prev"></div>
				<div class="swiper-button-next" slot="button-next"></div> -->
				<!-- <div class="swiper-scrollbar" slot="scrollbar"></div> -->
			</swiper>
			<!-- <div class="side-bar-zc"></div> -->
			<div class="side-bar">
				<ul class="warp">
					<li class="list">
						<a>手机 电话卡</a>
						<i class="fas fa-arrow-right"></i>
						<div class="zhezhao">
							<div class="zhezhao-list">
								<ul class="zhezhao-row">
									<li>
										<img src="../assets/img/item-box-1.png" alt="1">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-2.png" alt="2">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-3.jpg" alt="3">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-4.jpg" alt="4">
										<span>小米9</span>
									</li>
								</ul>
								<ul class="zhezhao-row">
									<li>
										<img src="../assets/img/item-box-1.png" alt="1">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-2.png" alt="2">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-3.jpg" alt="3">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-4.jpg" alt="4">
										<span>小米9</span>
									</li>
								</ul>
								<ul class="zhezhao-row">
									<li>
										<img src="../assets/img/item-box-1.png" alt="1">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-2.png" alt="2">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-3.jpg" alt="3">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-4.jpg" alt="4">
										<span>小米9</span>
									</li>
								</ul>
								<ul class="zhezhao-row">
									<li>
										<img src="../assets/img/item-box-1.png" alt="1">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-2.png" alt="2">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-3.jpg" alt="3">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-4.jpg" alt="4">
										<span>小米9</span>
									</li>
								</ul>
							</div>
						</div>
					</li>
					<li class="list"><a>电视 盒子</a>
						<i class="fas fa-arrow-right"></i>
						<div class="zhezhao">
							<div class="zhezhao-list">
								<ul class="zhezhao-row">
									<li>
										<img src="../assets/img/item-box-1.png" alt="1">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-2.png" alt="2">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-3.jpg" alt="3">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-4.jpg" alt="4">
										<span>小米9</span>
									</li>
								</ul>
								<ul class="zhezhao-row">
									<li>
										<img src="../assets/img/item-box-1.png" alt="1">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-2.png" alt="2">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-3.jpg" alt="3">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-4.jpg" alt="4">
										<span>小米9</span>
									</li>
								</ul>
								<ul class="zhezhao-row">
									<li>
										<img src="../assets/img/item-box-1.png" alt="1">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-2.png" alt="2">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-3.jpg" alt="3">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-4.jpg" alt="4">
										<span>小米9</span>
									</li>
								</ul>
								<ul class="zhezhao-row">
									<li>
										<img src="../assets/img/item-box-1.png" alt="1">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-2.png" alt="2">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-3.jpg" alt="3">
										<span>小米9</span>
									</li>
									<li>
										<img src="../assets/img/item-box-4.jpg" alt="4">
										<span>小米9</span>
									</li>
								</ul>
							</div>
						</div></li>
					<li class="list">笔记本 平板</li>
					<li class="list">家电 插线板</li>
					<li class="list">出行 穿戴</li>
					<li class="list">耳机 音响</li>
					<li class="list">电源 配件</li>
					<li class="list">生活 箱包</li>
				</ul>
			</div>


		</div>

	</div>
</template>

<script>
	import 'swiper/dist/css/swiper.css'
	import {
		swiper,
		swiperSlide
	} from 'vue-awesome-swiper'
	export default {
		name: 'Banner',
		data() {
			return {

				swiperOption: {
					pagination: {
						el: '.swiper-pagination',
						clickable: true,
					},
					navigation: {
						nextEl: '.swiper-button-next',
						prevEl: '.swiper-button-prev',
					},
					autoplay: {
						autoplay: true,
						disableOnInteraction: false,
					},
					loop: true,
					effect: 'cube',
				}
			}
		},
		components: {
			swiper,
			swiperSlide
		}
	}
</script>

<style scoped="scoped">
	@import url("../assets/fontawesome/css/all.css");
	.container {
		width: 100%;
		padding: 0 22px;
	}

	.swiper-box {
		width: 100%;
		margin: auto;
		/* background: #B0B0B0; */
		position: relative;
		overflow: hidden;

	}

	.swiper-slide img {
		width: 100%;
		background-size: cover;
	}

	.side-bar {
		position: absolute;
		/* top: -5px; */
		top: 0;
		left: 0;
		width: 264px;
		height: 99%;
		display: flex;
		flex-direction: column;
		flex: auto;
		z-index: 10;
		/* opacity: 0.5; */
		background-color: #55585a82;
		padding: 10px 0;
		/* overflow: hidden; */
	}

	/* 	.side-bar .warp{
		background:rgba(85,88,90,1);
	} */
	.side-bar .list {
		/* width: 100%; */
		/* background: rgba(85, 88, 90, 1); */
		height: 50px;
		text-align: center;
		line-height: 50px;
		display: flex;
		justify-content: space-between;
		padding: 0 30px;
		color: white;
		font-family: sans-serif;
	}
	.fa-arrow-right{
		line-height: 50px;
	}

	.swiper-button-prev {
		left: 280px;
	}

	.zhezhao {
		position: absolute;
		top: 0;
		left: 264px;
		width: 52.625rem;
		height: 100%;
		transform: translateY(-200%);
		background: rgba(255, 255, 255, 1);
		box-shadow: 0px 7px 6px 0px rgba(0, 0, 0, 0.11);
		z-index: 22;
		color: black;
		display: block;
		box-shadow:0px 7px 6px 0px rgba(0, 0, 0, 0.11);
		transition: .6s linear;
		
	}

	.list:hover {
		cursor: pointer;
		background: #FF6600;
		/* display: block; */
	}

	.list:hover .zhezhao {
		transform: translateX(0);
	}

	.zhezhao-list {
		width: 100%;
		height: 100%;
		/* 	background: #FF6600; */

	}

	.zhezhao-list .zhezhao-row {
		display: flex;
		padding: 10px 10px;
	}

	.zhezhao-list .zhezhao-row li {
		flex: 1;
		display: flex;
		justify-content: center;
		align-content: center;
		transition: .5s linear;
	}
	.zhezhao-list .zhezhao-row li:hover{
		transform: scale(1.1);
		color: #FF6600;
	}
	.zhezhao-list .zhezhao-row img {
		width: auto;
		height: 100%;
	}

	.zhezhao-list .zhezhao-row span {
		font-size: 16px;
		line-height: 80px;
		margin-left: 12px;
		font-family:FZLanTingHeiS-R-GB;
	}
</style>

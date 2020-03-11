<template>
	<div class="home">
		<Tabbar></Tabbar>
		<Serch></Serch>
		<Banner></Banner>
		<Ad></Ad>
		<Phone></Phone>
	</div>
</template>

<script>
	import Tabbar from '@/components/tabbar.vue'
	import Banner from '@/components/banner.vue'
	import Serch from '@/components/serch.vue'
	import Ad from '@/components/Ad.vue'
	import Phone from '@/components/Phone.vue'

	export default {
		name: 'Home',
		components: {
			Tabbar,
			Banner,
			Serch,
			Ad,
			Phone,
		}
	}
</script>

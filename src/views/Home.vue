<template>
	<div class="home">
		<Tabbar></Tabbar>
	</div>
</template>

<script>
	// @ is an alias to /src
	// import HelloWorld from '@/components/HelloWorld.vue'
	import Tabbar from '@/components/tabbar.vue'

	export default {
		name: 'Home',
		components: {
			// HelloWorld,
			Tabbar
		}
	}
</script>

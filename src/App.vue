<template>
	<div id="app">
		<!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
		<router-view />
	</div>
</template>

<style>
	* {
		padding: 0;
		margin: 0;
		box-sizing: border-box;
		text-decoration: none;
		list-style: none;
	}	
	#app{
		min-width: 700px;
		max-width: 1700px;
	}
</style>

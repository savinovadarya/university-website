<template>
	<div class="container">
		<Header />
		<Home />
	</div>
</template>

<script>
	import Header from './components/Header.vue'
	import Home from './components/Home.vue'

	export default {
		components: { Header, Home }, 
	}
</script>

<style scoped lang="scss">
	.container {
		max-width: 1200px;
		margin: 0 auto;
		padding: 0px 24px 0px 24px;
	}
</style>
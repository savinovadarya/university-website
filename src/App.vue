<template>
	<div class="container">
		<Header />
	</div>
</template>

<script>
	import Header from './components/Header.vue'

	export default {
		components: { Header }, 
	}
</script>

<style scoped lang="scss">
	.container {
		max-width: 1200px;
		margin: 0 auto;
	}
</style>
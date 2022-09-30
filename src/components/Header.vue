<template>
	<header class="header">
		<div class="header__logo logo">
			<Icon class="logo__image" name="logo"></Icon>
			<div class="logo__title logo-title">
				<span class="logo-title__sup">European</span>
				<span class="logo-title__sub">University of Arts</span>
			</div>
		</div>
		<nav class="header__nav nav">
			<ul class="nav__list list">
				<li class="list__item"><a href="#">About</a></li>
				<li class="list__item"><a href="#">Academics</a></li>
				<li class="list__item"><a href="#">Contact</a></li>
			</ul>
		</nav>
	</header>
</template>

<script>
	import Icon from './Icon.vue'

	export default {
		components: { Icon, }
	}
</script>

<style scoped lang="scss">
	.header {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-between;
		&__logo {
		}

		&__nav {
		}
	}
	.logo {
		display: flex;
		flex-direction: row;
		align-items: center;
		&__image {
		}

		&__title {
			display: flex;
			flex-direction: column;
		}
	}
	.logo-title {

		&__sup {
			font-size: 24px;
			font-weight: 600;
		}

		&__sub {
		}
	}
	.nav {

		&__list {
		}
		}
		.list {

		&__item {
		}
	}
</style>
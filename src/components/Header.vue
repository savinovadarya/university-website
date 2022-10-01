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
				<li class="list__item"><a class="list__link" href="#">About</a></li>
				<li class="list__item"><a class="list__link" href="#">Academics</a></li>
				<li class="list__item"><a class="list__link" href="#">Contact</a></li>
			</ul>
		</nav>
	</header>
</template>

<script>
	import Icon from './Icon.vue'

	export default {
		components: { Icon }
	}
</script>

<style scoped lang="scss">
	.header {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-between;
		padding: 24px 0px 24px 0px;
	}
	.logo {
		display: flex;
		flex-direction: row;
		align-items: center;
		&__image {
			margin: 0px 16px 0px 0px;
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
			margin: 0px 0px 4px 0px;
		}
		// &__sub {
		// }
	}
	// .nav {
	// }
	.list {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-between;
		&__item {
			font-size: 17px;
			font-weight: 700;
			color: var(--dark-grey);
			margin: 0px 48px 0px 0px;
			&:last-child {
				margin: 0px 0px 0px 0px;
			}
		}
		&__link {
			color: var(--dark-grey);
			text-decoration: none;
			transition: color .2s ease-in-out;
			&:hover {
				color: var(--black);
			}
		}
	}
</style>
<template>
	<div class="home">
		<div class="home__info info">
			<h2 class="info__sup">2022 | About us</h2>
			<h1 class="info__title">Visual history</h1>
			<p class="info__text">The Greatest temple of art that creates the future of Design and Art</p>
			<button class="info__btn">more</button>
		</div>
		<picture>
			<source type="image/webp" srcset="../assets/home-swiper-one@2x.webp 2x, ../assets/home-swiper-one.webp 1x">
			<source type="image/png" srcset="../assets/home-swiper-one@2x.png 2x, ../assets/home-swiper-one.png 1x">
			<img src="../assets/home-swiper-one.png" alt="">
		</picture>
	</div>
</template>

<script>

	export default {
	}
</script>

<style scoped lang="scss">
	.home {
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		height: calc(100vh - 100px);
		align-items: center;
	}
	.info {
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		&__sup {
			font-size: 20px;
			font-weight: 600;
			margin: 0px 0px 32px 0px;
		}
		&__title {
			max-width: 60%;
			font-size: 100px;
			font-weight: 700;
			margin: 0px 0px 40px 0px;
		}
		&__text {
			max-width: 60%;
			font-size: 20px;
			line-height: 1.3;
			margin: 0px 0px 56px 0px;
		}
		&__btn {
			background-color: transparent;
			padding: 0px 32px 8px 0px;
			color: var(--light-grey);
			border-bottom: 2px solid var(--light-grey);
		}
	}
	.slider {
	}

</style>
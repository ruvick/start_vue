<script setup>
	import Navbar from './Navbar';
</script>

<template>

		<footer class="footer">
			<div class="footer__container _container">
				<div class="footer__main">
					<div @click="$router.push('/')" class="footer__logo logo">
						<img src="logo.svg" loading="lazy" alt="Картинка">
					</div>
					<Navbar/>
				</div>
			</div>
		</footer>

</template>

<style lang="scss" scoped>

	.footer {
		position: relative;
		padding: 20px 0;
		border-top: 1px solid grey;
		.footer__main {
			display: flex;
			align-items: center;
			justify-content: space-between;
			gap: 30px;
		}
	}

</style>
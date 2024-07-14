<script setup>
	import Header from './components/Header.vue'
	import Footer from './components/Footer.vue'
</script>

<template>

	<Header/>

		<main class="page">

			<section class="page__about about">
				<div class="__container">

					<h1 class="title">Title</h1>

				</div>
			</section>

		</main>

		<Footer/>

</template>

<style lang="scss" scoped>

.title {
	font-size: 36px;
}

</style>

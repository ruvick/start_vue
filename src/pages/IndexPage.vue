<script setup>
	import MyButton from "@/components/UI/MyButton.vue";
</script>

<template>

	<main class="page">

		<section class="page__about about"> 
			<div class="__container">

				<h1 class="page__title title">Title</h1>

				<my-button>Создать</my-button>

				<my-button>Очистить</my-button>

			</div>
		</section>

	</main>

</template>

<style lang="scss" scoped>

	.title	{
		font-size: 36px;
		font-weight: 700;
		line-height: 1.3;
	}

</style>
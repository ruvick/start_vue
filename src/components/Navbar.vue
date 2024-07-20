<template>
	
	<div class="navbar">
		<my-button class="link" @click="$router.back">Назад</my-button>
		<my-button class="link" @click="$router.push('/users')">Пользователи</my-button>
		<my-button class="link" @click="$router.push('/about')">О нас</my-button>
	</div>

</template>

<script>

	export default {

	}

</script>

<style lang="scss" scoped>
	.navbar {
		display: flex;
		align-items: center;
		gap: 23px;
		flex-wrap: wrap;
		.link {
			font-weight: 500;
		}
	}
</style>
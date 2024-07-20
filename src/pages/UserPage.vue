<!-- Счечтик Options Api -->
<!-- <script>
	export default {
		// Храним данные
		data() {
			return {
				count: 0,
			}
		},
		// Изменяем данные
		methods: {
			increment() {
				this.count++
			}
		}
	}
</script> -->

<!-- Счетчик Composition Api  -->
<!-- <script setup>

	//импортируем функцию ref из Vue
	import {ref} from 'vue';

	let count = ref(0);

	function increment() {
		count.value++
	}

</script> -->

<script>

	export default {
		data() {
			return {
				dialogVisible: false,
				count: 0,
			}
		},
		methods: {
			showDialog() {
				this.dialogVisible = true;
			},
			increment() {
				this.count++
			}
		}
	}
	
</script>

<template>

	<main class="page">

		<section class="page__about about"> 
			<div class="__container">

				<h1 class="page__title title">Title</h1>

				<my-button>Создать</my-button>

				<my-button>Очистить</my-button>

				<my-button @click="showDialog">Открыть окно</my-button>

				<my-input type="text" placeholder="Описание" />

				<br>

				<h2>Счетчик: {{ count }} </h2>
				<br>
				<my-button @click="increment">+</my-button>

				<my-dialog v-model:show="dialogVisible">Модальное окно</my-dialog> 

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
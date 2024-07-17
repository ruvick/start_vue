<template>

	<Header/>
	<IndexPage/>
	<Footer/>

</template>

<script>

	import Header from '@/components/Header.vue'
	import IndexPage from '@/pages/IndexPage.vue';
	import Footer from '@/components/Footer.vue'

	export default {
		components: {
			Header,
			IndexPage,
			Footer,
		},
			data() {
			return {

			}
		},
	}


</script>

<style lang="scss">

</style>


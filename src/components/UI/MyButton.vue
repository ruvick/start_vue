<template>

	<button class="btn">
		<slot></slot>
	</button>
	
</template> 

<script>

	export default {
		name: 'my-button'
	}

</script>

<style lang="scss" scoped>
	.btn {
		display: inline-flex;
		justify-content: center;
		align-items: center;
		text-align: center;
		padding: 15px 23px;
		font-size: 16px;
		font-weight: 500;
		color: #fff;
		background: grey;
		border-radius: 3px;
		transition: all 0.3s ease 0s;

		@media (any-hover: hover) {
			&:hover {
				background: rgba(18, 11, 141, 0.5);
			}
		}
		
		&.fw {
			width: 100%;
		}
	}
</style>
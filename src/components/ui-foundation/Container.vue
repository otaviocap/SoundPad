<template>
	<div class="container">
		<slot></slot>
	</div>
</template>

<script setup lang="ts">

</script>

<style lang="scss">
	.container {
		background-color: $base-tone;
		width: 100vw;
		height: 100vh;
		position: fixed;

		display: grid;
		grid-template-areas: 
			'middle middle middle right right'
			'middle middle middle right right'
			'middle middle middle right right';
	}
</style>
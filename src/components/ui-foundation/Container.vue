<template>
	<div class="container">
		<slot></slot>
	</div>
</template>

<script setup lang="ts">

</script>

<style lang="scss">
	@import "@styles/variables.scss";

	.container {
		background-color: $base-tone;
		width: 100vw;
		height: 100vh;
	}
</style>
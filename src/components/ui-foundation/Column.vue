<template>
	<div class="column"><slot></slot></div>
</template>

<script setup lang="ts">

</script>
<style scoped lang="scss">
	.column {
		display: flex;
		flex-direction: column;
		align-items: baseline;
		justify-content: baseline;
	}
</style>
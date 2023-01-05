<template>
	<div class="row" :class="{wrap}">
		<slot></slot>
	</div>
</template>

<script setup lang="ts">
	const props = defineProps<{
		wrap?: boolean
	}>()
</script>

<style scoped lang="scss">
	.wrap {
		flex-wrap: wrap;
	}
	.row {
		display: flex;
		flex-shrink: 0;
		flex-grow: 0;
		flex-direction: row;
		align-items: flex-start;
	}
</style>
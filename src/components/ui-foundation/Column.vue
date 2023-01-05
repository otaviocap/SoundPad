<template>
	<div class="column" :class="{wrap}"><slot></slot></div>
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
	.column {
		display: flex;
		flex-direction: column;
		align-items: flex-start;
	}
</style>
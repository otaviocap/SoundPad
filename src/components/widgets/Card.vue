<template>
	<div class="card">
		<i class="ri-thunderstorms-line bg-icon"></i>
		<span>Thunder</span>
		<input type="range" />
		<Row class="action-row">
			<i class="ri-thunderstorms-line sm-icon"></i>
			<i class="ri-thunderstorms-line sm-icon"></i>
		</Row>
	</div>
</template>

<script setup lang="ts">
import Row from '../ui-foundation/Row.vue';


</script>

<style lang="scss" scoped>

$width: 150px;

.action-row {
	* {
		margin: 0px 5px 0px 5px;
	}
}

.card {
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: space-around;
	background-color: $base-tone;
	border-radius: $border-radius;
	width: $width;
	height: 200px;
	color: $accent-tone;

	box-shadow: $inner-shadow;

	margin: 10px;
	padding: 10px;
}

.card input[type="range"] {
  -webkit-appearance: none;
  appearance: none;
  width: 90%;
  height: 2px;
  background: $accent-tone;
  outline: none;

  border-radius: $border-radius;
}

.card input[type="range"]::-webkit-slider-thumb {
  -webkit-appearance: none;
  appearance: none;
  width: 12px;
  height: 12px;
  background: $accent-tone; 
  cursor: pointer;

  border-radius: $border-radius;
}

</style>
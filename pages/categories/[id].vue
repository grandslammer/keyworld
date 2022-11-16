<template>
	<div>
		<h1>{{ id }}</h1>
		<h3>Product description:</h3>
	</div>
</template>

<script setup lang="ts">
	const { id } = useRoute().params
</script>

<style scoped></style>

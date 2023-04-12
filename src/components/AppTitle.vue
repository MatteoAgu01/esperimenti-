<template>
	<header>
		<div class="d-flex flex-column align-items-center justify-content-center">
			<h1 class="m-0">{{ title }}</h1>
			<p>{{ subTitle }}</p>
		</div>
	</header>
</template>

<script>
export default {
	name: "appNav",
	data() {
		return {
			title: "hello world",
			subTitle: "my first page with Vite"
		}
	}
}
</script>

<style lang="scss" scoped></style>

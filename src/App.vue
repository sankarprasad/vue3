<template>
	<div>
		<h1>My Name is {{ firstName }} {{ lastName }}</h1>
		<div v-text="channel"></div>
	</div>
</template>

<script>
export default {
	name: "App",
	data() {
		return {
			firstName: "Sankar",
			lastName: "Panda",
			channel: "Hello World",
		};
	},
};
</script>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>

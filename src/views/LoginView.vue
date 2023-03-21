<template>
	<h1> Test Form </h1>
	<div class="inputContainer">
		<label for="email"> Email: </label>
		<input type="email" id="email">
	</div>

	<div class="inputContainer">
		<label for="email"> Password: </label>
		<input type="password" id="password">
	</div>

	<div class="buttonContainer">
		<button> Create </button>
		<button> Login </button>
		<button> See user </button>
	</div>
</template>

<style scoped>
.inputContainer {
	display: flex;
	flex-direction: column;
}

input {
	font-size: 1.5em;
}
.buttonContainer {
	display: flex;
	flex-direction: column;
	margin-top: 1em;
}

button {
	margin-bottom: 1em;
	padding: 1em 2em 1em 2em;
}
</style>
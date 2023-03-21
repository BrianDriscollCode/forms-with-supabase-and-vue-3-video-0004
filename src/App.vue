<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>

    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
		<RouterLink to="/login">Login</RouterLink>
      </nav>
    </div>
  </header>

  <div class="content">
	<RouterView />
  </div>

</template>

<style scoped>
nav {
	display: flex;
	justify-content: center;
}

nav a {
	padding: 1em;
}

.content {
	display: flex;
	align-items: center;
	flex-direction: column;
	width: 40%;
	border: solid 1px black;
	margin-left: auto;
	margin-right: auto;
}
</style>

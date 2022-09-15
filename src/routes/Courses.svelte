<script lang="ts">
	import Typewriter from 'svelte-typewriter'
</script>

<div class="container">
	<Typewriter interval={15} delay={0}>
		<h2>SVELTE WEB DEVELOPMENT</h2>
	</Typewriter>
	<Typewriter interval={15} delay={200}>
		<h2>RUST GAME DEVELOPMENT</h2>
	</Typewriter>
	<Typewriter interval={15} delay={650}>
		<h3>Coming 2023</h3>
	</Typewriter>
</div>

<style>
	.container {
		display: flex;
		flex-direction: column;
		text-align: left;
		float: left;
		max-height: 500px;
		overflow-y: hidden;
		overflow-x: hidden;
	}
	h3 {
		float: right;
		text-align: right;
	}
</style>

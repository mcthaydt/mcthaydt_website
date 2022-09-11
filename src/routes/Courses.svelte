<script lang="ts">
	import Typewriter from 'svelte-typewriter'
</script>

<div class="container">
	<Typewriter interval={15} delay={0}>
		<h2>SVELTE + TAURI</h2>
	</Typewriter>
	<Typewriter interval={15} delay={200}>
		<h2>BEVY + RUST</h2>
	</Typewriter>
	<Typewriter interval={15} delay={400}>
		<h2>GODOT ENGINE 4</h2>
	</Typewriter>
	<Typewriter interval={15} delay={600}>
		<h2>PRODUCT DESIGN FOR SOLO GAME DEVELOPERS</h2>
	</Typewriter>
	<Typewriter interval={15} delay={1450}>
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

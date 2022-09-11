<script lang="ts">
	import Typewriter from 'svelte-typewriter'
</script>

<div class="container">
	<Typewriter interval={15} delay={0}>
		<h2>2022 | CRISPY CABARET</h2>
	</Typewriter>
	<Typewriter interval={15} delay={200}>
		<h2>2022 | CABARET BALL</h2>
	</Typewriter>
	<Typewriter interval={15} delay={400}>
		<h2>2023 | WARUI RYOKO</h2>
	</Typewriter>
	<Typewriter interval={15} delay={600}>
		<h2>2023 | PARAMNESIA</h2>
	</Typewriter>
	<Typewriter interval={15} delay={800}>
		<h2>2024 | LIMERANCE</h2>
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
</style>

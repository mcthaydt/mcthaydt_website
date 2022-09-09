<script lang="ts">
	import Typewriter from 'svelte-typewriter'
</script>

<div class="container">
	<Typewriter interval={15}>
		<h2>2022 | CRISPY CABARET</h2>
		<h2>2022 | CABARET BALL</h2>
		<h2>2023 | WARUI RYOKO</h2>
		<h2>2023 | PARAMNESIA</h2>
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

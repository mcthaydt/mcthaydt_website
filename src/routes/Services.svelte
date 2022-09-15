<script lang="ts">
	import Typewriter from 'svelte-typewriter'
</script>

<div class="container">
	<Typewriter interval={15} delay={0}>
		<h1>717 INTERACTIVE IS ACCEPTING NEW CLIENTS IN OCTOBER</h1>
	</Typewriter>
	<Typewriter interval={15} delay={200}>
		<h2>HELPING CHICAGO NIGHTLIFE</h2>
	</Typewriter>
	<Typewriter interval={15} delay={950}>
		<h3>lightweight design studio</h3>
	</Typewriter>
</div>

<style>
	.container {
		text-align: left;
		max-height: 300px;
		overflow-y: auto;
		overflow-x: hidden;
	}
	h3 {
		text-align: right;
	}
</style>

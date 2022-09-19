<script lang="ts">
	import Typewriter from 'svelte-typewriter'
</script>

<div class="container">
	<Typewriter interval={15} delay={0}>
		<h1>SIDEREALOWL IS ACCEPTING NEW CLIENTS IN OCTOBER</h1>
	</Typewriter>
	<Typewriter interval={15} delay={200}>
		<h2>HELPING CHICAGO NIGHTLIFE</h2>
	</Typewriter>
	<div style="display: flex; align-items: center; justify-content: space-between;"> 
		<Typewriter interval={15} delay={950}>
			<h3>lightweight design studio</h3>
		</Typewriter>
		<Typewriter interval={15} delay={950}>
			<a href="https://contra.com/siderealowlstudio" style="margin-left: auto; padding-right: 1rem;">LINK</a>
		</Typewriter>
	</div>


	<Typewriter interval={15} delay={0}>
		<h1>MCTHAYDT IS ACCEPTING NEW CLIENTS IN NOVEMBER</h1>
	</Typewriter>
	<Typewriter interval={15} delay={200}>
		<h2>HELPING SOLO GAME DEVELOPERS</h2>
	</Typewriter>
	<div style="display: flex; align-items: center; justify-content: space-between;"> 
		<Typewriter interval={15} delay={950}>
			<h3>freelance rust game development</h3>
		</Typewriter>
		<Typewriter interval={15} delay={950}>
			<a href="https://www.fiverr.com/mcthaydt" style="margin-left: auto; padding-right: 1rem;">LINK</a>
		</Typewriter>
	</div>
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

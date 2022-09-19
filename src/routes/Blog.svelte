<script lang="ts">
	import Typewriter from 'svelte-typewriter'
</script>

<div class="container">

	<div style="width: 300px; height: auto; color: green; outline-style: ridge; border-radius: 3px; margin-top: 3rem; padding: 1rem;">
		<Typewriter interval={10}>
			<h2>McThayDT’s Branding Guide for Game Developers</h2>
			<h3>“A brand is a result. It’s a customer’s gut feeling about a product, service, or company.” - Marty Neumeier</h3>
		</Typewriter>
			<div style="display: flex; align-items: center; justify-content: space-between; padding-top: 5px;"> 
				<a href="https://medium.com/@mcthaydt/mcthaydts-branding-guide-for-game-developers-5559371f3370">Read Post</a>
			</div>
	</div>
</div>

<style>
	.container {
		width: 100%;
		max-height: 300px;
		overflow-y: auto;
		overflow-x: hidden;
		padding: 1rem;
	}
</style>

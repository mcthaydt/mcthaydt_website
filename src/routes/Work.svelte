<script lang="ts">
	import Typewriter from 'svelte-typewriter'
</script>


<div class="container">
	<div style="width: 300px; height: auto; color: green; outline-style: ridge; border-radius: 3px; margin-top: 3rem; padding: 1rem; display: block;">
		<Typewriter interval={15}>
			<h2>Cabaret Ball</h2>
		</Typewriter>
		<img src="https://user-images.githubusercontent.com/107786093/178137514-ac57850b-3306-45ca-ad08-a4827fe15f57.gif" alt="funny GIF" width="90%" height="75%">
		<Typewriter interval={15}>
		<h3>Precision-based 3D platformer controller for Godot Engine 4 Alpha Version 10 </h3> 
		</Typewriter >
		<div style="display: flex; align-items: center; justify-content: space-between; padding: 5px;"> 
			<a href="https://github.com/mcthaydt/CabaretBallSprint1_Prototype">Live Project</a>
			<a href="https://github.com/mcthaydt/CabaretBallSprint1_Prototype" style="margin-left: auto; padding-right: 1rem;">Source Code</a>
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

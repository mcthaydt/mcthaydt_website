<script lang="ts">
	import Typewriter from "svelte-typewriter";
</script>

<div class="container">
	<div
		style="width: 300px; height: auto; color: green; outline-style: ridge; border-radius: 3px; margin-top: 3rem; padding: 1rem; display: block;"
	>
		<Typewriter interval={15}>
			<h2>FLOORFIFTY</h2>
		</Typewriter>
		<img
			src="https://iili.io/HomZkPV.gif"
			alt="FLOORFIFTY GIF"
			width="90%"
			height="75%"
		/>
		<Typewriter interval={15}>
			<h3>Precision-based Competitive 2D Platformer</h3>
		</Typewriter>
		<Typewriter interval={15}>
			<h3>Created using Rust and Bevy Engine Version 0.9</h3>
		</Typewriter>
		<div
			style="display: flex; align-items: center; justify-content: space-between; padding: 5px;"
		>
			<a
				href="https://github.com/mcthaydt/FloorFiftyVerticalSlice"
				style="margin-left: auto; padding-right: 1rem;"
			>
				Source Code
			</a>
		</div>
	</div>

	<div
		style="width: 300px; height: auto; color: green; outline-style: ridge; border-radius: 3px; margin-top: 3rem; padding: 1rem; display: block;"
	>
		<Typewriter interval={15}>
			<h2>R.E.S.S.E.T App</h2>
		</Typewriter>
		<img
			src="https://iili.io/HomtnRe.gif"
			alt="R.E.S.S.E.T GIF"
			width="90%"
			height="75%"
		/>
		<Typewriter interval={15}>
			<h3>Lifestyle and Wellness Mobile App</h3>
		</Typewriter>
		<Typewriter interval={15}>
			<h3>Created using React Native (CLI), Javascript, and CSS</h3>
		</Typewriter>
		<div
			style="display: flex; align-items: center; justify-content: space-between; padding: 5px;"
		>
			<a href="https://www.ressetstudio.com">Live Project</a>
		</div>
	</div>

	<div
		style="width: 300px; height: auto; color: green; outline-style: ridge; border-radius: 3px; margin-top: 3rem; padding: 1rem; display: block;"
	>
		<Typewriter interval={15}>
			<h2>McThayDT Website</h2>
		</Typewriter>
		<img
			src="https://iili.io/HomZGFS.gif"
			alt="McThayDT GIF"
			width="90%"
			height="75%"
		/>
		<Typewriter interval={15}>
			<h3>Professional Website for Dawson McThay</h3>
		</Typewriter>
		<Typewriter interval={15}>
			<h3>Created using Svelte, HTML, CSS, and Javascript</h3>
		</Typewriter>
		<div
			style="display: flex; align-items: center; justify-content: space-between; padding: 5px;"
		>
			<a href="https://mcthaydt.netlify.app">Live Project</a>
			<a
				href="https://github.com/mcthaydt/mcthaydt_website"
				style="margin-left: auto; padding-right: 1rem;">Source Code</a
			>
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

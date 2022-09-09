<script lang="ts">
	import Typewriter from 'svelte-typewriter'
</script>

<div class="container">
	<Typewriter interval={10}>
		<h3>Red Flags 🚩</h3>
		<ul>
			<li>I dropped out of college halfway through my junior year.</li>
			<li>You'd audibly gasp if you saw my GPA.</li>
			<li>I'm a Scorpio male.</li>
		</ul>
		<h3>Green Flags 😍</h3>
		<ul>
			<li>I attended Vanderbilt University. (CompSci + Econ) </li>
			<li>I ran a freelance video production service that generated over 5 figures before the age of 21.</li>
			<li>I can hold an L-Sit for over 30-seconds.</li>
		</ul>
	</Typewriter>
</div>

<style>
	.container {
		text-align: left;
		float: left;
		max-height: 300px;
		overflow-y: scroll;
		overflow-x: hidden;
		margin-left: 3%;
	}
	ul {
		list-style-type: circle;
		margin-left: 0.1vw; 
	}
	li {
		list-style-type: circle;
	}
</style>


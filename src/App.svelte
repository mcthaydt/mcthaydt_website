<script lang="ts">
	import Typewriter from "svelte-typewriter";
	import Router from "svelte-spa-router";

	import About from "./routes/About.svelte";
	import Blog from "./routes/Blog.svelte";
	import Work from "./routes/Work.svelte";
	import Products from "./routes/Products.svelte";
	import Services from "./routes/Services.svelte";
	import Courses from "./routes/Courses.svelte";
	import NotFound from "./routes/404.svelte";

	let routes = {
		"/": Work,
		"/About": About,
		"/Blog": Blog,
		"/Work": Work,
		"/Products": Products,
		"/Services": Services,
		"/Courses": Courses,
		"*": NotFound,
	};
	// don't forget to readd courses
</script>

<main>
	<header>
		<Typewriter mode={"scramble"} scrambleDuration={350}>
			<h1>Dawson McThay</h1>
			<h2>Product-Focused Software Developer</h2>
		</Typewriter>
		<Typewriter mode={"scramble"} scrambleDuration={450}>
			<nav>
				<a href="#/About/">About</a>
				<a href="#/Work/">Work</a>
				<a href="#/Blog/">Blog</a>
				<a href="#/Products/">Products</a>
				<a href="#/Services/">Services</a>
			</nav>
		</Typewriter>
	</header>
	<div class="container">
		<Router {routes} />
	</div>
	<footer>
		<Typewriter mode={"scramble"} scrambleDuration={350}>
			<a href="https://www.tiktok.com/@crispyowl717">TikTok</a>
			<a href="https://twitter.com/crispyowl717">Twitter</a>
			<a href="https://github.com/mcthaydt">Github</a>
			<a href="https://www.reddit.com/user/crispyowl717">Reddit</a>
			<a href="https://www.instagram.com/crispyowl717/">Instagram</a>
			<a href="https://crispyowl717.com">Music</a>
		</Typewriter>
	</footer>
</main>

<style>
	h1,
	h2,
	nav,
	footer {
		text-align: center;
	}
	h2 {
		font-weight: normal;
	}
	header {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		align-items: center;
		padding-top: 3%;
		padding-bottom: 3%;
	}
	header a {
		padding-right: 1.5%;
		padding-left: 1.5%;
	}
	footer {
		position: fixed;
		left: 0;
		bottom: 0;
		width: 100%;
		text-align: center;
		padding-top: 3%;
		padding-bottom: 3%;
	}
	footer a {
		padding-left: 3%;
	}
	a {
		text-transform: uppercase;
		font-weight: bold;
	}
</style>

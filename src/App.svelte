<script lang="ts">
	import Router from 'svelte-spa-router'

	import About from './routes/About.svelte'
	import Blog from './routes/Blog.svelte'
	import Work from './routes/Work.svelte'
	import Products from './routes/Products.svelte'
	import Services from './routes/Services.svelte'
	import Courses from './routes/Courses.svelte'
	import NotFound from './routes/404.svelte'

	let routes = {
		"/": Work,
		"/About": About,
		"/Blog": Blog,
		"/Work": Work,
		"/Products": Products,
		"/Services": Services,
		"/Courses": Courses,
		"*": NotFound
	}
</script>

<main>
	<h1>Dawson McThay</h1>
	<h2>Software Engineer + Product Designer</h2>

	<nav>
		<a href="#/About/">About</a> |
		<a href="#/Work/">Work</a> |
		<a href="#/Blog/">Blog</a> |
		<a href="#/Products/">Products</a> |
		<a href="#/Services/">Services</a> |
		<a href="#/Courses/">Courses</a>
	</nav>

	<Router {routes} />

</main>

<footer>
	<a href="TikTok">TikTok</a>
	<a href="Twitter">Twitter</a>
	<a href="YouTube">YouTube</a>
	<a href="Reddit">Reddit</a>
	<a href="Medium">Medium</a>
	<a href="Soundcloud">Soundcloud</a>
	<a href="Instagram">Instagram</a>
</footer>

<style>
</style>

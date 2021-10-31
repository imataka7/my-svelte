<script>
	import { Router, Route } from 'svelte-routing';
	import About from './About.svelte';
	import Home from './Home.svelte';
</script>

<main>
	<Router>
		<Route path="/about" component="{About}" />
		<Route path="/" component="{Home}" />
	</Router>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
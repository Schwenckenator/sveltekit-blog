<script>
	import '$lib/styles/pico.orange.min.css';
	let { children } = $props();
</script>

<header>I'm a header</header>

<main>
	{@render children()}
</main>

<footer>I'm a footer</footer>

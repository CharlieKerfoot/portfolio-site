<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<link
		rel="icon"
		type="image/png"
		href="/src/lib/assets/favicon/favicon-96x96.png"
		sizes="96x96"
	/>
	<link rel="icon" type="image/svg+xml" href="/src/lib/assets/favicon/favicon.svg" />
	<link rel="shortcut icon" href="/src/lib/assets/favicon/favicon.ico" />
	<link
		rel="apple-touch-icon"
		sizes="180x180"
		href="/src/lib/assets/favicon/apple-touch-icon.png"
	/>
	<link rel="manifest" href="/src/lib/assets/favicon/site.webmanifest" />
</svelte:head>

{@render children()}

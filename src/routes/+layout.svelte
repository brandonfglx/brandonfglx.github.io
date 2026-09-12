<script lang="ts">
	import './layout.css';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href="https://avatars.githubusercontent.com/u/173737496" /></svelte:head>
{@render children()}

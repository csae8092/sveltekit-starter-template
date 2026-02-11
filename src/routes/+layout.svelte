<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import { app_config } from '$lib/constants';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>{app_config.title_short}</title>
</svelte:head>
{@render children()}

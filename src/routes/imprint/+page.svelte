<script lang="ts">
	let { data } = $props();
</script>

<svelte:head>
	<title>Imprint</title>
</svelte:head>
<div class="prose">
	{@html data.imprint_body}
</div>

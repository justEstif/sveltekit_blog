<script lang="ts">
	import { page } from '$app/stores'
</script>

<svelte:head>
	<title>Error</title>
</svelte:head>

<div class="error">
	<h1>{$page.status}: {$page.error?.message}</h1>
</div>

<style>
	.error {
		height: 100%;
		display: grid;
		place-content: center;
	}
</style>

<script lang="ts">
	import favicon from '$lib/assets/favicon.ico';

	let { children } = $props();
	import '@sakun/system.css';
	// import '../../static/' /
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}

<style>
	:global(body) {
		font-family: 'Menlo', 'Monaco', 'Courier New', monospace;
		background-color: #dddddd;
	}

	:global(*) {
		box-sizing: border-box;
	}
</style>

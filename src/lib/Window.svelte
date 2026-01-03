<script lang="ts">
	let { title, children } = $props();
</script>

<div class="window">
	<div class="title-bar">
		<h1 class="title">{title}</h1>
	</div>
	<div class="separator"></div>

	<div class="window-pane">
		{@render children()}
	</div>
</div>

<style>
	.window-pane {
		font-size: 10pt;
		text-align: center;
	}
</style>

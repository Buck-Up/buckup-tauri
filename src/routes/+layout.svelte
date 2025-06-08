<script lang="ts">
	import "../app.css";

	let { children } = $props();
</script>

<div class="grid grid-rows-[auto_1fr_auto]">
	<header class="bg-surface-900 p-4">Smart Sync</header>

	<div
		class="container mx-auto grid grid-cols-1 xl:grid-cols-[200px_minmax(0px,_1fr)_200px]"
	>
		{@render children()}
	</div>
</div>

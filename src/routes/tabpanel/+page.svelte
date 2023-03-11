<script>
	import { getContext } from 'svelte';
	import Tab from '../tab/+page.svelte';

	const panel = {};
	const { registerPanel, selectedPanel } = getContext(Tab);

	registerPanel(panel);
</script>

{#if $selectedPanel === panel}
	<slot></slot>
{/if}
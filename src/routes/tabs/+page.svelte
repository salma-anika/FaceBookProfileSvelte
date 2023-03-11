<script>
	import { getContext } from 'svelte';
	import Tab from '../tab/+page.svelte';

	const tab = {};
	const { registerTab, selectTab, selectedTab } = getContext(Tab);

	registerTab(tab);
</script>



<button class:selected="{$selectedTab === tab}" on:click="{() => selectTab(tab)}">
	<slot></slot>
</button>



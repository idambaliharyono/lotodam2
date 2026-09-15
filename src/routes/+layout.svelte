<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
<div class="mx-auto w-full max-w-[430px] font-body text-[9px] tracking-[3px]">
	{@render children()}
</div>

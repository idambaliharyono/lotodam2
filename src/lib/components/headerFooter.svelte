<script lang="ts">
	let { variant } = $props();
</script>

{#if variant === '1'}
	<div class="flex flex-row justify-between px-2 py-1 text-white">
		<span>DWIJAKSARA</span>
		<span>WIDYA</span>
	</div>
{:else}
	<div class="flex flex-row justify-between px-2 py-1 text-white">
		<span>9/10/26</span>
		<span>PAWIWAHAN</span>
	</div>
{/if}

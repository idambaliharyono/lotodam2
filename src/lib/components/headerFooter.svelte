<script lang="ts">
	let { variant, position = 'top' }: { variant: string; position?: Position } = $props();
	type Position = 'top' | 'bottom';
	const positionClasses: Record<Position, string> = {
		top: 'top-0',
		bottom: 'bottom-0'
	};
</script>

{#if variant === '1'}
	<div
		class="absolute left-0 w-full {positionClasses[
			position
		]} flex flex-row justify-between px-2 py-1 text-white"
	>
		<span>DWIJAKSARA</span>
		<span>WIDYA</span>
	</div>
{:else}
	<div
		class="absolute left-0 w-full {positionClasses[
			position
		]} flex flex-row justify-between px-2 py-1 text-white"
	>
		<span>9/10/26</span>
		<span>PAWIWAHAN</span>
	</div>
{/if}

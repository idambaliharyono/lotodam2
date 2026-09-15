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
		class="absolute left-0 w-full text-[10px] tracking-[1.5px] {positionClasses[
			position
		]} flex flex-row justify-between px-2.5 py-3.5 text-white italic"
	>
		<span>DWIJAKSARA</span>
		<span>WIDYA</span>
	</div>
{:else}
	<div
		class="absolute left-0 w-full text-[11px] tracking-[1.5px] {positionClasses[
			position
		]} flex flex-row justify-between px-2.5 py-3.5 text-white"
	>
		<span>9/10/26</span>
		<span>PAWIWAHAN</span>
	</div>
{/if}

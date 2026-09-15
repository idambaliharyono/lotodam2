<script>
	let { name, orderText, fatherName, motherName, bgSrc, photoSrc } = $props();
</script>

<!---->
<!-- <div class="relative h-1/2 border border-red-500 bg-white font-body"> -->
<!-- 	<div class="h-1/2"></div> -->
<!-- 	<div class="h-1/2"> -->
<!-- 		<div class="h-20/40"></div> -->
<!-- 		<div class="h-20/40"> -->
<!-- 			<h1 class="mb-4 text-center font-heading text-base">Pengantin</h1> -->
<!-- 			<p class="mb-0.5 text-center font-body tracking-[1.5px]">{name}</p> -->
<!-- 			<div class="mx-auto w-15/24"> -->
<!-- 				<div class="space-y-0 leading-tight tracking-[1.5px]"> -->
<!-- 					<p>{orderText}</p> -->
<!-- 					<p>{fatherName}</p> -->
<!-- 					<p>& {motherName}</p> -->
<!-- 				</div> -->
<!-- 			</div> -->
<!-- 		</div> -->
<!-- 	</div> -->
<!-- 	<div class="absolute top-0 left-0 h-1/2"> -->
<!-- 		<img src={bgSrc} alt="" class="h-full w-full object-cover" /> -->
<!-- 	</div> -->
<!-- 	<div class="absolute top-1/2 left-1/2 aspect-[8/9] w-9/20 -translate-1/2 overflow-hidden"> -->
<!-- 		<img src={photoSrc} alt="" class="h-full w-full object-cover object-center" /> -->
<!-- 	</div> -->
<!-- </div> -->
<div class="relative h-1/2 bg-white font-body">
	<div class="h-1/2"></div>

	<div class="absolute top-0 left-0 h-1/2">
		<img src={bgSrc} alt="" class="h-full w-full object-cover" />
	</div>

	<!-- Photo: unchanged position -->
	<div
		class="absolute top-1/2 left-1/2 aspect-[8/9] w-9/20 -translate-x-1/2 -translate-y-1/2 overflow-hidden"
	>
		<img src={photoSrc} alt="" class="h-full w-full object-cover object-center" />
	</div>

	<!-- Text: anchored to the photo's own box, not the outer container -->
	<div class="absolute top-1/2 left-1/2 aspect-[8/9] w-9/20 -translate-x-1/2 -translate-y-1/2">
		<div class="absolute top-full left-1/2 mt-2 w-max max-w-xs -translate-x-1/2 text-center">
			<h1 class="mb-4 font-heading text-base">Pengantin</h1>
			<p class="mb-0.5 tracking-[1.5px]">{name}</p>
			<div class="space-y-0 px-2 text-left leading-tight tracking-[1.5px]">
				<p>{orderText}</p>
				<p>{fatherName}</p>
				<p>& {motherName}</p>
			</div>
		</div>
	</div>
</div>

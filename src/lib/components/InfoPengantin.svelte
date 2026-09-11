<script>
	let {
		name,
		orderText,
		fatherName,
		motherName,
		logoSrc = 'https://res.cloudinary.com/dzzfgwj4/image/upload/v1789117606/images.png',
		photoSrc = 'https://res.cloudinary.com/dzzfgwj4/image/upload/v1789149926/static.xx.fbcdn.webp'
	} = $props();
</script>

<div class="relative h-1/2 bg-white">
	<div class="h-1/2"></div>
	<div class="h-1/2">
		<div class="h-3/5"></div>
		<div class="h-2/5">
			<h1 class="mb-1 text-center text-base">Pengantin</h1>
			<p class="text-center">{name}</p>
			<div class="mx-auto w-13/24">
				<div class="leading-tight">
					<p>{orderText}</p>
					<p>{fatherName}</p>
					<p>& {motherName}</p>
				</div>
			</div>
		</div>
	</div>
	<div class="absolute top-0 left-0 h-1/2">
		<img src={logoSrc} alt="" />
	</div>
	<div class="absolute top-1/2 left-1/2 w-1/2 -translate-1/2">
		<img src={photoSrc} alt="" />
	</div>
</div>

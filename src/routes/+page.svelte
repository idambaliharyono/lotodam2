<script lang="ts">
	import HeaderFooter from '$lib/components/headerFooter.svelte';
	import InfoPengantin from '$lib/components/InfoPengantin.svelte';
</script>

<!-- state1  -->
<div></div>
<!-- state2 -->
<div></div>
<!-- state3 -->
<div>
	<!-- page1 -->
	<div class="relative h-screen">
		<div class="relative h-1/2 bg-amber-900">
			<HeaderFooter variant="1"></HeaderFooter>
			<div
				class="absolute top-4/9
        left-1/2 w-2/5 -translate-1/2 px-2 text-justify text-white"
			>
				<h1 class="mb-6 text-center text-lg">Om Swastyastu</h1>
				<!-- <span -->
				<!-- 	>"Ya Tuhan Yang Maha Pengasih, anugrahkanlah kepada pasangan ini tanpa terpisahkan, -->
				<!-- 	panjang umur, semoga pernikahan ini dianugrahkan putra-putri dan cucu yang memberi -->
				<!-- 	penghiburan, tinggal di rumah yang penuh kebahagiaan"</span -->
				<!-- > -->
				<div class="text-justify leading-relaxed tracking-wider [text-align-last:justify]">
					<p>"Ya Tuhan Yang Maha Pen-</p>
					<p>gasih, anugrahkanlah kepa-</p>
					<p>da pasangan ini tanpa ter-</p>
					<p>pisahkan, panjangkan umur,</p>
					<p>semoga pernikahan ini dia-</p>
					<p>anugrahkan putra-putri dan</p>
					<p>cucu yang memberi peng-</p>
					<p>hiburan, tinggal di rumah</p>
					<p>yang penuh kebahagiaan."</p>
				</div>
				<p class="mt-2 text-center">(Reg Weda X. 85.42)</p>
			</div>
			<!-- <div class="mx-auto mt-20 flex flex-col text-center text-white"> -->
			<!-- 	<span>Om Swastyastu</span> -->
			<!-- 	<div class="w-0.5"> -->
			<!-- 	</div> -->
			<!-- </div> -->
		</div>
		<div class="relative h-1/2 bg-white">
			<div class=" [] absolute top-4/11 left-1/2 w-5/6 -translate-1/2">
				<div class=" w-2/3 text-justify leading-relaxed tracking-wider">
					Atas Asung Kertha Wara Nugraha Ida Sang Hyang Widhi Wasa/Tuhan Yang Maha Esa, Kami
					Bermaksud Mengundang Bapak/Ibu/Saudara/i, pada Acara Manusa Yadnya - Pawiwahan anak kami.
				</div>
			</div>
		</div>
		<img
			src="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789117606/images.png"
			alt=""
			class="absolute top-1/2 left-1/2 w-5/6 -translate-x-1/2 -translate-y-1/2 object-cover"
		/>
	</div>

	<div class="h-screen">
		<InfoPengantin
			name="I Gusti Bagus Agung Dwijaksara, S.Arsl., IALI"
			orderText="putra ke dua dari pasangan"
			fatherName="I Gusti Ngurah Kanca"
			motherName="Ida Ayu Puja Widiastuti"
			photoSrc="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789317205/belum.jpg"
			bgSrc="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789317205/belum.jpg"
		/>
		<InfoPengantin
			name="Ni Putu Widya Maheswari Karantika Putri, S.Par., M.Tr.Par"
			orderText="putri pertama dari pasangan"
			fatherName="Dr. I ketut Kanten, A.Par., S.E., M.M., CHA., CHE.,"
			motherName="Ni Komang Kartika, S.E"
			photoSrc="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789317205/pengantin2.jpg"
			bgSrc="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789317205/pengantin2bg.jpg"
		/>
	</div>

	<div class="mt-10 h-screen">
		<div
			class="mx-6 h-1/2
      "
		>
			<div class="flex w-full gap-3.5">
				<!-- Left column: photo 1 + caption -->
				<div class="flex w-1/3 flex-col">
					<div class="aspect-square overflow-hidden">
						<img
							src="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789317217/3-1.jpg"
							class="h-full w-full object-cover"
							alt="pengantin"
						/>
					</div>
					<p class="mt-3">
						Apabila Bapak/Ibu/Saudara/i berkenan hadir dan memberikan doa restu kepada kami
					</p>
				</div>

				<!-- Right column: intro text, then photo row -->
				<div class="flex w-2/3 flex-col">
					<p>
						Merupakan suatu kehormatan dan kebahagiaan bagi kami sekeluarga pada acara sederhana ini
					</p>

					<div class="mt-3 flex gap-3.5">
						<div class="aspect-square flex-1 overflow-hidden">
							<img
								src="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789317217/3-2.jpg"
								class="h-full w-full object-cover object-center"
								alt="pengantin"
							/>
						</div>
						<div class="aspect-[3/4] flex-1 overflow-hidden">
							<img
								src="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789317217/3-3.jpg"
								class="h-full w-full object-cover object-center"
								alt="pengantin"
							/>
						</div>
					</div>
				</div>
			</div>

			<div class="mt-10 flex w-full gap-3.5">
				<!-- Left column: photo 1 + caption -->
				<div class="flex w-1/3">
					<div class="aspect-square overflow-hidden">
						<img
							src="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789317217/3-4.jpg"
							class="h-full w-full object-cover"
							alt="pengantin"
						/>
					</div>
				</div>

				<!-- Right column: intro text, then photo row -->
				<div class="flex w-2/3 flex-col">
					<div class="flex gap-3.5">
						<div class="aspect-square flex-1 overflow-hidden">
							<img
								src="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789317217/3-5.jpg"
								class="h-full w-full object-cover object-center"
								alt="pengantin"
							/>
						</div>
						<div class="aspect-[3/4] flex-1 overflow-hidden">
							<img
								src="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789317217/3-6.jpg"
								class="h-full w-full object-cover object-center"
								alt="pengantin"
							/>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

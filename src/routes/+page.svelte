<script lang="ts">
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
			<div class="flex flex-row justify-between px-2 pt-1 text-white">
				<span>DWIJAKSARA</span>
				<span>WIDYA</span>
			</div>
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

	<!-- page2 -->
	<!-- <div class="h-screen"> -->
	<!-- 	<div class="relative h-1/2 bg-white"> -->
	<!-- 		<div class="h-1/2"></div> -->
	<!-- 		<div class="h-1/2"> -->
	<!-- 			<div class="h-3/5"></div> -->
	<!-- 			<div class="h-2/5"> -->
	<!-- 				<h1 class="mb-1 text-center text-base">Pengantin</h1> -->
	<!-- 				<p class="text-center">I Gusti Bagus Agung Dwijaksara, S.Arsl., IALI</p> -->
	<!-- 				<div class="mx-auto w-7/12"> -->
	<!-- 					<div class="leading-3"> -->
	<!-- 						<p>putra ke dua dari pasangan</p> -->
	<!-- 						<p>I Gusti Ngurah Kanca</p> -->
	<!-- 						<p>& Ida Ayu Puja Widiastuti</p> -->
	<!-- 					</div> -->
	<!-- 				</div> -->
	<!-- 			</div> -->
	<!-- 		</div> -->
	<!-- 		<div class="absolute top-0 left-0 h-1/2"> -->
	<!-- 			<img src="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789117606/images.png" alt="" /> -->
	<!-- 		</div> -->
	<!-- 		<div class="absolute top-1/2 left-1/2 w-1/2 -translate-1/2"> -->
	<!-- 			<img -->
	<!-- 				src="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789149926/static.xx.fbcdn.webp" -->
	<!-- 				alt="" -->
	<!-- 			/> -->
	<!-- 		</div> -->
	<!-- 	</div> -->
	<!-- 	<div class="relative h-1/2 bg-white"> -->
	<!-- 		<div class="h-1/2"></div> -->
	<!-- 		<div class="h-1/2"> -->
	<!-- 			<div class="h-3/5"></div> -->
	<!-- 			<div class="h-2/5"> -->
	<!-- 				<h1 class="mb-1 text-center text-base">Pengantin</h1> -->
	<!-- 				<p class="text-center">Ni Putu Widya Maheswari Karantika Putri, S.Par., M.Tr.Par</p> -->
	<!-- 				<div class="mx-auto w-7/12"> -->
	<!-- 					<div class=" leading-3"> -->
	<!-- 						<p>putri pertama dari pasangan</p> -->
	<!-- 						<p>Dr. I ketut Kanten, A.Par., S.E., M.M., CHA., CHE.,</p> -->
	<!-- 						<p>& Ni Komang Kartika, S.E</p> -->
	<!-- 					</div> -->
	<!-- 				</div> -->
	<!-- 			</div> -->
	<!-- 		</div> -->
	<!-- 		<div class="absolute top-0 left-0 h-1/2"> -->
	<!-- 			<img src="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789117606/images.png" alt="" /> -->
	<!-- 		</div> -->
	<!-- 		<div class="absolute top-1/2 left-1/2 w-1/2 -translate-1/2"> -->
	<!-- 			<img -->
	<!-- 				src="https://res.cloudinary.com/dzzfgwj4/image/upload/v1789149926/static.xx.fbcdn.webp" -->
	<!-- 				alt="" -->
	<!-- 			/> -->
	<!-- 		</div> -->
	<!-- 	</div> -->
	<!-- </div> -->

	<div class="h-screen">
		<InfoPengantin
			name="I Gusti Bagus Agung Dwijaksara, S.Arsl., IALI"
			orderText="putra ke dua dari pasangan"
			fatherName="I Gusti Ngurah Kanca"
			motherName="Ida Ayu Puja Widiastuti"
		/>
		<InfoPengantin
			name="Ni Putu Widya Maheswari Karantika Putri, S.Par., M.Tr.Par"
			orderText="putri pertama dari pasangan"
			fatherName="Dr. I ketut Kanten, A.Par., S.E., M.M., CHA., CHE.,"
			motherName="Ni Komang Kartika, S.E"
		/>
	</div>
</div>

<script lang="ts">
	import { Icon, Home, Ticket, MagnifyingGlass, ChevronRight } from 'svelte-hero-icons';
	import { register } from 'swiper/element/bundle';

	register();
</script>

<div class="max-w-md min-h-screen bg-slate-900 mx-auto overflow-hidden pb-28">
	<div class="flex items-center justify-between text-slate-200 mt-4 px-4">
		<img width="120" src="bioskuy!.png" alt="Bioskuy!">
		<img class="rounded-xl" width="36" height="36" src="https://api.dicebear.com/9.x/adventurer-neutral/svg?seed=Jameson" alt="Fikri">
	</div>
	<swiper-container
		class="mt-6 -mx-4"
		space-between={20}
		slides-per-view={1.5}
		centered-slides={true}
		loop={true}
	>
		<swiper-slide>
			<img class="rounded-xl h-full mx-auto"
					 src="https://media.21cineplex.com/webcontent/gallery/pictures/174332714933197_925x527.jpg"
					 alt="Pabrik Gula">
		</swiper-slide>
		<swiper-slide>
			<img class="rounded-xl h-full mx-auto"
					 src="https://media.21cineplex.com/webcontent/gallery/pictures/174332714933197_925x527.jpg"
					 alt="Pabrik Gula">
		</swiper-slide>
		<swiper-slide>
			<img class="rounded-xl h-full mx-auto"
					 src="https://media.21cineplex.com/webcontent/gallery/pictures/174332714933197_925x527.jpg"
					 alt="Pabrik Gula">
		</swiper-slide>
	</swiper-container>
	<div class="flex items-center justify-between px-4 mt-6">
		<h2 class="text-sm text-center text-slate-200 font-medium">Sedang Tayang</h2>
		<button class="bg-linear-to-r from-[#BB2827] to-red-500 py-1 pl-3 pr-1 rounded-xl text-slate-200 flex items-center gap-0.5 text-xs text-shadow-md">
			Semua
			<Icon src={ChevronRight} alt="Ticket icon" size="20" micro />
		</button>
	</div>
	<swiper-container
		class="mt-4 -mx-4"
		space-between={20}
		slides-per-view={1.5}
		centered-slides={true}
		loop={true}
	>
		<swiper-slide>
			<img class="rounded-xl h-full mx-auto"
					 src="https://m.media-amazon.com/images/M/MV5BMDAyNmVhZGQtYTRhMi00MWM4LWIzZjktYWFhYWQxYzYyNjAzXkEyXkFqcGc@._V1_FMjpg_UX1012_.jpg"
					 alt="Pabrik Gula">
		</swiper-slide>
		<swiper-slide>
			<img class="rounded-xl h-full mx-auto"
					 src="https://m.media-amazon.com/images/M/MV5BMDAyNmVhZGQtYTRhMi00MWM4LWIzZjktYWFhYWQxYzYyNjAzXkEyXkFqcGc@._V1_FMjpg_UX1012_.jpg"
					 alt="Pabrik Gula">
		</swiper-slide>
		<swiper-slide>
			<img class="rounded-xl h-full mx-auto"
					 src="https://m.media-amazon.com/images/M/MV5BMDAyNmVhZGQtYTRhMi00MWM4LWIzZjktYWFhYWQxYzYyNjAzXkEyXkFqcGc@._V1_FMjpg_UX1012_.jpg"
					 alt="Pabrik Gula">
		</swiper-slide>
	</swiper-container>
	<h3 class="text-center mt-4 text-base text-slate-200 font-medium">Pabrik Gula Uncut</h3>
	<button class="bg-linear-to-r from-[#BB2827] to-red-500 py-3 px-5 rounded-xl text-slate-200 flex items-center gap-2 text-sm mx-auto mt-4 text-shadow-md">
		<Icon src={Ticket} alt="Ticket icon" size="26" solid />
		Pesan Tiket
	</button>
	<div
		class="fixed bottom-0 inset-x-0 max-w-md bg-slate-600/25 backdrop-blur-xl mx-auto p-5 flex items-center justify-around text-slate-200 border-t border-white/20">
		<button class="text-[#BB2827]">
			<Icon src={Home} alt="Home icon" size="26" solid />
		</button>
		<button>
			<Icon src={MagnifyingGlass} alt="Ticket icon" size="26" outline />
		</button>
		<button>
			<Icon src={Ticket} alt="User Circle icon" size="26" outline />
		</button>
	</div>
</div>
<!-- Features Section: Vertical Cards -->
<script>
  import { fade } from 'svelte/transition';
  import { inview } from 'svelte-inview';
  let isInView;
	import { Image } from "@unpic/svelte";
</script>
<div
class="wrapper"
use:inview={{ unobserveOnEnter: true, rootMargin: '-20%' }}
on:change={({ detail }) => {
	isInView = detail.inView;
}}
>
{#if isInView}
<div in:fade class=" overflow-hidden">
	<div class="container xl:max-w-7xl mx-auto px-4 py-16 lg:px-8 lg:py-10">
		<div class="flex flex-col lg:flex-row lg:items-center space-y-12 lg:space-y-0 lg:space-x-20">
			<!-- Heading -->
			<div class="lg:w-5/12 xl:w-5/12 md:py-12 space-y-10 ">
				<div>
					<div class="text-sm uppercase font-bold tracking-wider mb-1 text-rose-700">
						Ge din bil kärlek den förtjänar
					</div>
					<h2 class="text-3xl md:text-4xl font-extrabold mb-4">
						Vi tar hand om din bil, du njuter av körningen
					</h2>
					<h3 class="text-lg md:text-xl md:leading-relaxed font-medium text-gray-500">
						Vi erbjuder olika tjänster inom Bilvård. Med vår poleringstjänst får du en perfekt finish och den bästa glansen. Vi erbjuder också utvändig rekond och invändig rekond för att se till att din bil ser ut som ny.

Vår motortvätt kommer att rengöra din motor och hålla den i toppskick. För att skydda din bil från framtida skador rekommenderar vi också vårt keramiska lackskydd. Det gör det enklare att tvätta bilen och skyddar samtidigt bilens lack, förhöjer glansen på bilen och ger det ultimata skyddet mot repor och skador.
					</h3>
				</div>
			</div>
			<!-- END Heading -->

			<!-- Features in Cards -->
			<div class="lg:w-7/12 xl:w-7/12 flex-none relative ">
				<div
					class="pattern-dots-xl opacity-20 absolute top-0 left-0 w-48 h-64 md:mt-20 transform -translate-x-10 -translate-y-10"
				/>
				<div
					class="pattern-dots-xl  opacity-20 absolute bottom-0 right-0 w-48 h-64 md:mb-20 transform translate-x-10 translate-y-10"
				/>
				<div class="relative flex flex-col md:flex-row md:space-x-6 space-y-6 md:space-y-0">
					<div class="md:w-2/5 md:mt-24 space-y-6">
						<div
							class="group bg-gray-800 transition ease-out duration-200 border-2 border-gray-700 rounded-2xl hover:border-orange-300"
						>
							<Image  layout="constrained"
							width={800}
							height={600}   src="https://i.ibb.co/Y2DmV8T/hero.webp" class="rounded-2xl " alt="bmw bil" srcset="" />
						</div>
						<div
							class="group bg-gray-800 transition ease-out duration-200 border-2 border-gray-700 rounded-2xl hover:border-red-300"
						>
							<Image  layout="constrained"
							width={800}
							height={600}   src="https://i.ibb.co/gmTLnXv/bmw4.webp" class="rounded-2xl " alt="bmw bil" srcset="" />
						</div>
					</div>
					<div class="md:w-2/5 space-y-6">
						<div
							class="group bg-gray-800  transition ease-out duration-200 border-2 border-gray-700 rounded-2xl hover:border-emerald-300"
						>
							<Image  layout="constrained"
							width={800}
							height={600}    src="https://i.ibb.co/Fgx5rtL/Foto-2022-10-15-18-01-15.jpg" class="rounded-2xl " alt="bmw bil" srcset="" />
						</div>
						<div
							class="group bg-gray-800  transition ease-out duration-200 border-2 border-gray-700 rounded-2xl hover:border-purple-300"
						>
							<Image  layout="constrained"
							width={800}
							height={600}   src="https://i.ibb.co/phvSdMT/bmw3.webp" class="rounded-2xl " alt="bmw bil" srcset="" />
						</div>
					</div>
				</div>
			</div>
			<!-- END Features in Cards -->
		</div>
	</div>
</div>
<!-- END Features Section: Vertical Cards -->
{/if}
</div>
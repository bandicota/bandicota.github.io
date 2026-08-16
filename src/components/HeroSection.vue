<template>
	<section class="w-full bg-white">
		<!-- World illustration + Siluscia title -->
		<div
			class="relative flex h-[295px] w-full items-start justify-center overflow-hidden pt-[30px] md:h-[397px] md:pt-[60px] xl:h-[669px] xl:pt-[60px]"
		>
			<img
				src="/images/hero-bg.webp"
				alt=""
				class="absolute inset-0 h-full w-full object-cover"
			/>
			<img
				src="/images/siluscia-title.webp"
				alt="Siluscia, The Sea of Dreams"
				class="relative z-10 h-[80px] w-[211px] object-contain md:h-[115px] md:w-[342px] xl:h-[192px] xl:w-[621px]"
			/>
		</div>

		<!-- Tagline, pirate art, subtitle -->
		<div class="flex flex-col items-center px-[30px] py-[60px] xl:py-[120px]">
			<div
				class="flex w-full max-w-[812px] flex-col items-center gap-5 xl:gap-[20px]"
			>
				<p
					class="text-center font-body text-[16px] font-light italic leading-[1.3] tracking-[0.3px] text-brand md:text-[20px] xl:text-[24px]"
				>
					Beyond the Gateways whisper tales of a boundless sea, where a thousand
					shores drift endlessly; caught in the pull of an ancient tree that
					dwarfs the highest peaks.
				</p>

				<img
					src="/images/siluscia-pirate.webp"
					alt="Pirate woman with red hair, a large hook for a left hand, holding a fireball"
					class="h-[402px] w-full object-contain md:h-[437px] xl:h-[703px]"
				/>

				<p
					class="text-center font-body text-[16px] font-medium leading-[1.39] tracking-[0.2px] text-brand md:text-[20px] xl:text-[24px]"
				>
					A handcrafted system-agnostic TTRPG zine introducing a wondrous new
					world of pirates and adventure to explore.
				</p>
			</div>
		</div>
	</section>
</template>

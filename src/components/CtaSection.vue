<script setup lang="ts">
import SocialLinks from "./SocialLinks.vue";
</script>

<template>
	<section class="w-full bg-white">
		<div
			class="flex flex-col items-center px-[30px] py-[60px] xl:px-[120px] xl:py-[120px]"
		>
			<div
				class="flex w-full max-w-[1100px] flex-col items-center gap-[30px] md:flex-row md:items-start xl:flex-row xl:items-start"
			>
				<img
					src="/images/zine-booklet.webp"
					alt="Zine booklet mockup with a shadow"
					class="h-[253px] w-[308px] shrink-0 object-contain md:h-[370px] md:w-[269px] xl:h-[470px] xl:w-[396px]"
				/>

				<div
					class="flex flex-1 flex-col items-center justify-center gap-[30px] md:items-start xl:gap-[60px]"
				>
					<p
						class="text-center font-body text-[16px] font-medium leading-[1.39] tracking-[0.2px] text-brand md:text-left md:text-[20px] xl:text-left xl:text-[24px]"
					>
						A new adventure awaits. Listen to that ache in your chest. Find your
						courage, gather your friends, and set sail into a wondrous world
						where dreams become reality.
					</p>

					<div
						class="flex flex-col items-center gap-5 md:items-start xl:items-start"
					>
						<p
							class="font-display text-[16px] font-black uppercase leading-[1.39] tracking-[-0.52px] text-brand md:text-[24px] xl:text-[26px]"
						>
							FOllow Us On:
						</p>
						<SocialLinks />
					</div>
				</div>
			</div>
		</div>
	</section>
</template>

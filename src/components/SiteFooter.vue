<script setup lang="ts">
import SocialLinks from "./SocialLinks.vue";
</script>

<template>
	<footer class="w-full bg-white">
		<div
			class="flex flex-col items-center gap-10 px-[30px] py-[30px] md:flex-row md:items-center md:justify-between md:gap-[60px] md:px-[60px] md:py-[60px] xl:px-[120px]"
		>
			<div
				class="flex flex-col items-center gap-10 md:flex-1 md:items-start md:justify-between md:self-stretch"
			>
				<SocialLinks />
				<p
					class="font-display text-[16.22px] font-black uppercase leading-[1.1] tracking-[0.811px] text-ink"
				>
					&copy; 2026 Bandicota Collective
				</p>
			</div>
			<img
				src="/images/logo-v.webp"
				alt="Bandicota"
				class="h-[217px] w-[188px] shrink-0 object-contain"
			/>
		</div>
	</footer>
</template>

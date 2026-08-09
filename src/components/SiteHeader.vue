<script setup lang="ts">
import SocialLinks from "./SocialLinks.vue";
</script>

<template>
	<header
		class="flex items-center justify-between px-3 py-5 md:px-[30px] md:py-[30px]"
	>
		<a href="/" aria-label="Bandicota Collective — home">
			<img
				src="/images/logo-h.webp"
				alt="Bandicota Collective"
				class="h-[57px] w-auto md:h-[66px] xl:h-[95px]"
			/>
		</a>
		<SocialLinks />
	</header>
</template>

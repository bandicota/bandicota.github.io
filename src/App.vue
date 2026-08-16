<script setup lang="ts">
import SiteHeader from "./components/SiteHeader.vue";
import HeroSection from "./components/HeroSection.vue";
import ShowcaseSection from "./components/ShowcaseSection.vue";
import CtaSection from "./components/CtaSection.vue";
import AboutSection from "./components/AboutSection.vue";
import SiteFooter from "./components/SiteFooter.vue";
</script>

<template>
	<SiteHeader />

	<main class="w-full">
		<HeroSection />
		<ShowcaseSection />
		<CtaSection />
		<AboutSection />
	</main>

	<SiteFooter />
</template>

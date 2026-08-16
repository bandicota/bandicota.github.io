<script setup lang="ts">
const socials = [
	{
		name: "Instagram",
		href: "https://www.instagram.com/bandicota.collective/",
		icon: "/icons/instagram.svg",
	},
	{
		name: "Facebook",
		href: "https://www.facebook.com/bandicota",
		icon: "/icons/facebook.svg",
	},
	{
		name: "Bluesky",
		href: "https://bsky.app/profile/bandicota.bsky.social",
		icon: "/icons/bluesky.svg",
	},
];
</script>

<template>
	<div class="flex items-center gap-4">
		<a
			v-for="social in socials"
			:key="social.name"
			:href="social.href"
			target="_blank"
			rel="noopener noreferrer"
			:aria-label="social.name"
			class="shrink-0"
		>
			<img :src="social.icon" :alt="social.name" class="h-[30px] w-auto" />
		</a>
	</div>
</template>

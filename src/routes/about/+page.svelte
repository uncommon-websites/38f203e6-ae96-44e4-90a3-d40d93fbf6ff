<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Data-driven decisions",
			description: "Every campaign optimization is backed by real-time performance data, not guesswork."
		},
		{
			title: "Startup mentality",
			description: "We understand the urgency and resource constraints that drive early-stage companies."
		},
		{
			title: "Transparent results",
			description: "Clear attribution and honest reporting help you understand exactly where your ad spend goes."
		}
	];
</script>

<SecondaryHero
	title="Smarter ads, fewer regrets"
	subtitle="Marketing clarity for busy teams"
	imageSrc="/generated/image-a-modern-naturally-lit-office-space-with.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started Peter after hearing the same story over and over—startups burning precious budget on ads with no ROI. Hiring help was expensive and inconsistent. Doing it solo? Confusing at best. We knew there had to be a better way.",
		"So we built Peter: a performance marketing partner that acts like a top-tier media buyer—smart, fast, and always learning. Our platform is grounded in real-time data and shaped by hundreds of campaigns across industries.",
		"Today, our mission is simple: help startups grow without the guesswork. Because when your ads work, your business does too."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Meet the founder."
	subtitle="Building performance marketing that actually works."
	stakeholders={[
		{
			name: "Aniket Singh",
			position: "Founder & CEO",
			bio: "Building Peter to help startups grow without the guesswork in performance marketing.",
			image: "/generated/image-modern-editorial-style-professional-head.webp"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Stop wasting ad spend"
	subtitle="Start seeing real ROI"
	description="Join the marketing managers who've transformed their campaigns with Peter's data-driven approach. No more guessing, no more budget waste."
	imageSrc="/generated/image-a-professional-team-of-diverse-marketing.webp"
/>

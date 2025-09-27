<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Smarter ads. Better results."
	subtitle="Launch campaigns that learn and improve on their own."
	imageSrc="/generated/image-a-modern-editorial-documentary-photograp.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders" 
	logoUrls={[
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/warby-parker.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/glossier.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Sofia Martinez",
			position: "VP Marketing",
			company: "GrowthCo",
			quote:
				"We went from zero to profitable ads in under 48 hours. Peter saved us weeks and helped cut initial test budgets by half.",
			image: "/generated/image-professional-headshot-of-a-confident-his.webp"
		},
		{
			name: "David Chen",
			position: "Marketing Director",
			company: "LaunchPad",
			quote:
				"No more digging through dashboards. Peter surfaces what's working so we can make confident decisions faster.",
			image: "/generated/image-professional-headshot-of-a-successful-as.webp"
		},
		{
			name: "Amara Johnson",
			position: "Head of Growth",
			company: "ScaleUp",
			quote:
				"Hiring freelancers was hit-or-miss. With Peter, we cut out the delays and errors—our CAC is down 27%.",
			image: "/generated/image-professional-headshot-of-an-experienced-.webp"
		}
	]}
/>

<Features
	generating
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />

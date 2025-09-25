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
			title: "Speed matters",
			description: "We understand that in M&A, the first to connect often wins. Every feature we build prioritizes speed and efficiency."
		},
		{
			title: "Data-driven precision",
			description: "We turn market signals into actionable insights, helping brokers target the right sellers at the right time."
		},
		{
			title: "Broker success",
			description: "Your deals closed are our success metrics. We measure ourselves by the value we create for M&A professionals."
		}
	];
</script>

<SecondaryHero
	title="Less hunting. More deals."
	subtitle="Built for brokers who move fast"
	imageSrc="/generated/image-a-group-of-professionals-engaged-in-a-ca.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Before Legacy Point, M&A brokers hit the same wall every day—hours of manual hunting, cold calls to unqualified prospects, and watching good deals slip away to competitors who moved faster. Our founders saw this frustration firsthand: talented brokers spending more time searching than selling, missing opportunities in the $1M-$50M market where speed and precision matter most.",
		"Maximilian Jendrall and Mike Ballas founded Legacy Point to solve this fundamental problem through technology. We analyzed seller behavior, dug into data signals, and spoke with brokers frustrated by traditional lead generation platforms. The result was a new way to surface business owners likely to sell soon—before anyone else knows they're considering an exit.",
		"Today, Legacy Point transforms how M&A professionals source deals. We help brokers connect with motivated business owners in less time, with less friction, delivering qualified seller leads that turn into real conversations and closed transactions. We're building the intelligent sourcing engine that puts brokers ahead of the competition, not behind it."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team."
	subtitle="Built by experts who understand M&A."
	stakeholders={[
		{
			name: "Mike Ballas",
			position: "Founder & CEO",
			bio: "Experienced M&A professional focused on solving the deal sourcing challenge through technology.",
			image: "/generated/image-modern-documentary-style-ceo-headshot-in.webp"
		},
		{
			name: "Maximilian Jendrall",
			position: "Founder & CTO",
			bio: "Technology leader building intelligent systems to connect brokers with qualified business sellers.",
			image: "/generated/image-modern-documentary-style-cto-headshot-in.webp"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Stop hunting. Start closing."
	subtitle="Join the brokers moving faster"
	description="Transform how you source deals with Legacy Point. Connect with motivated business owners ready to sell, reduce manual prospecting time, and focus on what you do best—closing transactions."
	imageSrc="/generated/image-a-medium-distance-candid-photograph-of-a.webp"
/>

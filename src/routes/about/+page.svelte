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
			title: "Innovation",
			description: "Constantly challenging the status quo to create better solutions."
		},
		{
			title: "Integrity",
			description: "Building trust through transparent actions and honest communication."
		},
		{
			title: "Impact",
			description: "Measuring our success by the positive change we create for our clients."
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
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Maximilian Jendrall",
			position: "Founder & CTO",
			bio: "Technology leader building intelligent systems to connect brokers with qualified business sellers.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to source smarter?"
	subtitle="Connect with qualified sellers faster"
	description="Join M&A brokers who are already using Legacy Point to identify motivated business owners and close more deals."
/>

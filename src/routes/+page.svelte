<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
</script>

<CustomerCardHero
	centered={true}
	title="Connect with qualified sellers faster than ever"
	subtitle="Legacy Point helps M&A brokers identify and connect with qualified business owners ready to sell, streamlining your deal flow and increasing revenue potential."
	customers={[
		{
			name: "Michael Chen",
			position: "M&A Broker",
			imageSrc: "/generated/image-professional-middle-aged-businessman-in-.webp"
		},
		{
			name: "Sarah Martinez",
			position: "Business Owner",
			imageSrc: "/generated/image-professional-businesswoman-in-corporate-.webp"
		},
		{
			name: "Robert Williams",
			position: "Managing Partner",
			imageSrc: "/generated/image-senior-male-executive-in-a-business-suit.webp"
		},
		{
			name: "Jennifer Thompson",
			position: "Investment Advisor",
			imageSrc: "/generated/image-professional-female-business-owner-in-an.webp"
		},
		{
			name: "David Rodriguez",
			position: "Deal Broker",
			imageSrc: "/generated/image-middle-aged-male-broker-in-professional-.webp"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/deloitte.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/pwc.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/ey.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/kpmg.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	generating
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
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

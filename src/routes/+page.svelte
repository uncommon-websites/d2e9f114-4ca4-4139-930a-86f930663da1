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
	testimonials={[
		{
			name: "Marcus Patterson",
			position: "Senior M&A Broker",
			company: "Patterson Capital Advisors",
			quote:
				"Legacy Point cut our lead qualification time from 3 weeks to 4 days. We closed $12M in deals last quarter that we would have missed with manual prospecting.\nThe platform paid for itself in the first month.",
			image: "/generated/image-headshot-of-a-professional-middle-aged-m.webp"
		},
		{
			name: "Victoria Chen",
			position: "Managing Partner",
			company: "Chen & Associates",
			quote:
				"Before Legacy Point, we were cold-calling hundreds of prospects with a 2% success rate. Now we connect with pre-qualified sellers ready to transact.\nOur deal flow increased 340% while reducing research costs by $85,000 annually.",
			image: "/generated/image-headshot-of-a-professional-female-busine.webp"
		},
		{
			name: "Robert Steinberg",
			position: "Principal Broker",
			company: "Steinberg Investment Banking",
			quote:
				"Legacy Point eliminated the guesswork in seller identification. We closed a $28M manufacturing deal within 6 weeks of first contact.\nThe risk of pursuing unqualified leads is now virtually zero.",
			image: "/generated/image-headshot-of-a-senior-male-investment-ban.webp"
		}
	]}
/>

<Features
	title="Accelerate your deal flow"
	subtitle="Purpose-built tools that connect M&A brokers with qualified sellers, streamlining every step from lead identification to deal closure."
	features={[
		{
			title: "Intelligent seller matching",
			description: "Our AI-powered algorithms identify business owners ready to sell in your target market. Connect with qualified sellers in the $1M-$50M range faster than manual prospecting.",
			imageSrc: "/generated/image-a-candid-moment-in-a-modern-elegant-boar.webp"
		},
		{
			title: "Comprehensive deal pipeline",
			description: "Track every opportunity from initial contact to closing with automated follow-ups and milestone reminders. Never lose track of potential deals again.",
			imageSrc: "/generated/image-a-candid-moment-in-a-sophisticated-offic.webp"
		},
		{
			title: "Market intelligence dashboard",
			description: "Access real-time market data, valuation trends, and competitive insights to position deals strategically and maximize success rates.",
			imageSrc: "/generated/image-a-candid-scene-in-a-refined-office-setti.webp"
		},
		{
			title: "Secure deal collaboration",
			description: "Share sensitive documents and communicate with buyers, sellers, and advisors through our encrypted platform designed for M&A confidentiality.",
			imageSrc: "/generated/image-a-naturally-lit-modern-office-where-two-.webp"
		},
		{
			title: "Automated lead qualification",
			description: "Pre-screen potential sellers using customizable criteria to focus your time on the most promising opportunities that match your deal preferences.",
			imageSrc: "/generated/image-a-candid-networking-scene-in-a-contempor.webp"
		},
		{
			title: "Revenue optimization insights",
			description: "Track commission potential, deal velocity, and ROI across your entire pipeline to identify patterns that drive higher revenue outcomes.",
			imageSrc: "/generated/image-a-small-group-of-professionals-in-a-mode.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />

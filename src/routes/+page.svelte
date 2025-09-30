<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
</script>

<CenteredTextOnlyHero
	title="No more fund admin headaches"
	subtitle="Allocator One replaces 7 disconnected systems with one seamless platform, so you can focus on deals—not paperwork."
	imageSrc="/generated/image-a-warm-softly-lit-interior-scene-with-a-.webp"
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/a16z.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/greylock.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/bessemer.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Allocator One transforms fragmented fund administration into unified AI-native infrastructure, replacing 7+ disconnected systems with one seamless platform. We serve first-time fund managers at emerging VC firms who want to focus on sourcing deals—not navigating months of administrative complexity. Our proprietary Ledger One technology eliminates operational overhead, turning administrative burden into strategic advantage."
/>

<Testimonials
	testimonials={[
		{
			name: "Leona Mei",
			position: "Managing Partner",
			company: "Ascent Circle Ventures",
			quote:
				"Allocator One saved us 4+ months of setup and gave us real-time insights from day one. We went from drowning in spreadsheets to having complete portfolio visibility in minutes.",
			image: "/generated/image-professional-headshot-of-an-asian-woman-.webp"
		},
		{
			name: "Emil Kwan",
			position: "Founding GP",
			company: "Nightjar Capital",
			quote:
				"We cut admin hours by 85% and finally have a single source of truth for fund data. No more juggling seven different systems or worrying about compliance gaps.",
			image: "/generated/image-professional-headshot-of-an-asian-man-wi.webp"
		},
		{
			name: "Isabelle Laurent",
			position: "Managing Partner",
			company: "Atlas Fund Partners",
			quote:
				"The cost savings are substantial—we eliminated three separate platforms and reduced our admin team by half. Now our team focuses on deals, not data entry.",
			image: "/generated/image-professional-headshot-of-a-european-woma.webp"
		}
	]}
/>

<Features
	title="Why fund managers choose Allocator One"
	subtitle="Transform operational complexity into strategic advantage with AI-native infrastructure built for the next generation of private markets."
	features={[
		{
			title: "AI-native unified ledger",
			description: "Our proprietary Ledger One technology replaces 7+ disconnected systems with a single source of truth. Experience unprecedented data integrity and real-time portfolio visibility that legacy providers simply cannot match.",
			imageSrc: "/generated/image-a-professional-fund-manager-sits-confide.webp"
		},
		{
			title: "One-click migration guarantee",
			description: "Seamlessly transfer your entire fund history in minutes, not months. Our proprietary migration process preserves every data point while eliminating the operational downtime that traditionally plagues fund transitions.",
			imageSrc: "/generated/image-a-group-of-professionals-in-business-att.webp"
		},
		{
			title: "12-hour service guarantee",
			description: "When fund managers need answers, time matters. Our 12-hour service level agreement ensures you never wait days for critical administrative support, backed by our team of Wall Street experts.",
			imageSrc: "/generated/image-two-professionals-exchange-a-firm-handsh.webp"
		},
		{
			title: "Real-time portfolio intelligence",
			description: "Transform administrative data into strategic insights with our AI-powered analytics engine. Make informed investment decisions with dynamic valuations and automated LP reporting that scales with your fund.",
			imageSrc: "/generated/image-a-team-of-business-professionals-stands-.webp"
		},
		{
			title: "Automated compliance & reporting",
			description: "Focus on deals, not paperwork. Our platform handles complex regulatory requirements across 15+ jurisdictions, automatically generating audit-ready reports while maintaining institutional-grade compliance standards.",
			imageSrc: "/generated/image-a-clean-organized-desk-in-a-stylish-offi.webp"
		},
		{
			title: "Global regulatory reach",
			description: "Scale internationally with confidence through our established presence in the world's top PE/VC jurisdictions. From London to Singapore, we handle local regulatory requirements while maintaining unified operations.",
			imageSrc: "/generated/image-a-panoramic-view-of-a-modern-financial-d.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />

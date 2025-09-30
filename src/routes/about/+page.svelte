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
			title: "Beyond software: AI-native infrastructure",
			description: "We're not retrofitting legacy systems—we're architecting the future of fund administration from the ground up, purpose-built for the generative AI era."
		},
		{
			title: "Allocate or stagnate",
			description: "Capital allocation drives alpha generation. Our 12-hour SLA ensures fund managers can focus on deals and portfolio strategy instead of administrative complexity."
		},
		{
			title: "Silicon Valley technology meets Wall Street expertise",
			description: "Our founders experienced fund administration pain firsthand. We combine institutional knowledge with cutting-edge technology to turn operational burden into competitive advantage."
		}
	];
</script>

<SecondaryHero
	title="Built for fund managers, not back offices"
	subtitle="Transforming fragmented fund administration into unified portfolio intelligence"
	imageSrc="/generated/image-a-professional-fund-manager-stands-by-a-.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Most first-time fund managers face an impossible choice: spend months navigating 7+ disconnected administration systems, or focus on what they do best—sourcing deals and generating alpha. We watched talented managers get buried in operational complexity when they should have been building their portfolios. The fragmented infrastructure wasn't just inefficient; it was actively preventing the next generation of fund managers from succeeding.",
		"Michael and Felix experienced this pain firsthand in their Wall Street careers. They saw how legacy systems created unnecessary friction at every step—from fund setup to LP reporting to portfolio tracking. So they did what only seasoned operators could: they built Allocator One from the ground up, combining Silicon Valley technology with Wall Street expertise. Our proprietary Ledger One infrastructure isn't retrofitted legacy software—it's AI-native architecture designed for the generative AI era.",
		"Today, Allocator One transforms administrative burden into strategic advantage. We've consolidated those 7+ fragmented systems into one intelligent platform that grows with you—from fund launch to $1B+ AUM. Our 13 portfolio funds and LP partners like Budweiser, Henkel, and Fortino Capital trust us because we're not just software providers—we're partners who understand that great fund management starts with great infrastructure. When fund managers can focus on deals instead of admin, everyone wins."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our founders."
	subtitle="Silicon Valley technology meets Wall Street expertise."
	stakeholders={[
		{
			name: "Michael Ströck",
			position: "Founding Partner",
			bio: "Michael experienced the operational complexity of managing private market funds across multiple fragmented systems. His deep understanding of fund administration pain points drives his mission to create unified AI-native infrastructure that transforms administrative burden into strategic advantage.",
			image: "/generated/image-a-professional-business-executive-in-a-t.webp"
		},
		{
			name: "Felix Staeritz",
			position: "Founding Partner",
			bio: "Felix witnessed firsthand how data silos and legacy systems constrain fund managers' ability to generate alpha. His experience with the inefficiencies of traditional fund administration fuels his conviction to build the next generation of integrated financial infrastructure.",
			image: "/generated/image-a-business-leader-in-formal-attire-posed.webp"
		},
		{
			name: "Heidi Strunz",
			position: "Partner for Operations, Brand & Communications",
			bio: "Heidi leads our operations and communications strategy, ensuring our partnerships with fund managers translate into exceptional experiences and meaningful business outcomes.",
			image: "/generated/image-a-professional-businesswoman-in-a-smart-.webp"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Trusted by industry leaders."
	subtitle="Selected limited partners and portfolio funds"
	stakeholders={[
		{
			name: "Henkel",
			image: "https://logo.clearbit.com/henkel.com"
		},
		{
			name: "Budweiser",
			image: "https://logo.clearbit.com/budweiser.com"
		},
		{
			name: "Heise Media Group",
			image: "https://logo.clearbit.com/heise.de"
		},
		{
			name: "Fortino Capital",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "EOVC",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Stop managing seven tools. Start managing capital."
	subtitle="Allocator One transforms administrative burden into strategic advantage"
	description="Join 13+ portfolio funds and LPs like Budweiser, Henkel, and Fortino Capital who trust our AI-native infrastructure to power $1B+ in assets. One-click migration gets you live in hours, not months."
	imageSrc="/generated/image-a-professional-fund-manager-in-a-modern-.webp"
/>

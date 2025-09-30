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
			title: "Relentless execution",
			description: "We share a passion for solving hard problems with our partners and deliver results that matter."
		},
		{
			title: "Partnership focus",
			description: "Our 12-hour service level agreement isn't just a promise—it's how we build lasting relationships."
		},
		{
			title: "Community building",
			description: "Supporting first and second-generation fund managers through infrastructure that scales with their success."
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
			bio: "Michael experienced the operational complexity of managing private market funds across multiple fragmented systems. His deep understanding of fund administration pain points drives his mission to create unified AI-native infrastructure.",
			image: "/generated/image-a-confident-business-executive-stands-at.webp"
		},
		{
			name: "Felix Staeritz",
			position: "Founding Partner",
			bio: "Felix witnessed firsthand how data silos and legacy systems constrain fund managers' ability to generate alpha. His experience with the inefficiencies of traditional fund administration fuels his conviction to build the next generation of integrated financial infrastructure.",
			image: "/generated/image-a-professional-fund-manager-stands-by-a-.webp"
		},
		{
			name: "Heidi Strunz",
			position: "Partner for Operations, Brand & Communications",
			bio: "Heidi leads our operations and communications strategy, ensuring our partnerships with fund managers translate into exceptional experiences and meaningful business outcomes.",
			image: "/generated/image-a-diverse-group-of-financial-professiona.webp"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Trusted by industry leaders."
	subtitle="Selected limited partners and portfolio funds"
	stakeholders={[
		{
			name: "Fortino Capital",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "EOVC",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Heise Media Group",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to transform your fund administration?"
	subtitle="From fragmented systems to unified intelligence"
	description="Join the fund managers already using Allocator One to focus on what matters most—generating alpha for their investors."
/>

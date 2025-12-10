<script>
    import Navbar from "$lib/components/Navbar.svelte";
    import Hero from "$lib/components/Hero.svelte";
    import Gateway from "$lib/components/Gateway.svelte";
    import Market from "$lib/components/Market.svelte";
    import NativeCurrency from "$lib/components/NativeCurrency.svelte";
    import AgentFrameworks from "$lib/components/AgentFrameworks.svelte";
    import Deployment from "$lib/components/Deployment.svelte";
    import FeatureGrid from "$lib/components/FeatureGrid.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<div class="min-h-screen bg-white font-sans antialiased selection:bg-purple-100 selection:text-purple-900">
    <Navbar />
    <main>
        <Hero />
        <Gateway />
        <Market />
        <NativeCurrency />
        <AgentFrameworks />
        <Deployment />
        <FeatureGrid />
    </main>
    <Footer />
</div>


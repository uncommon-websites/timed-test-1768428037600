<script lang="ts">
	import Navbar from '$lib/components/Navbar.svelte';
	import Hero from '$lib/components/Hero.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<main class="min-h-screen bg-background text-foreground selection:bg-accent/20">
	<Navbar />
	<Hero />
	<Footer />
</main>

<script>
  import Hero from '$lib/components/Hero.svelte';
  import HowItWorks from '$lib/components/HowItWorks.svelte';
  import CTA from '$lib/components/CTA.svelte';
</script>

<main>
  <Hero />
  <HowItWorks />
  <CTA />
</main>

<style>
  main {
    min-height: 100vh;
    background: #2000FF;
    font-family: 'Inter', sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
</style>

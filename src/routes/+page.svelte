<script>
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Pericles</title>
	<meta name="description" content="Pericles Landing Page" />
</svelte:head>

<section>
	<h1>
		Pericles
	</h1>
</section>


<style>
    section {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    h1 {
        color: var(--color-title);
        font-size: 60px;
    }
</style>
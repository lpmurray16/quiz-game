<script>
    import Header from "$lib/Header.svelte";
</script>

<Header />
<div class="about">
    <h1 class="text-xl">About</h1>
    <p>
        This is a quiz game. It is still being built. I am building the entire
        game using SvelteKit. My name is Logan Murray and you can check out more
        of my work by clicking MORE in the navbar.
    </p>
</div>

<style>
    .about {
        padding: 1rem;
    }
    h1 {
        margin: 20px auto;
        text-align: center;
    }
</style>

<script>
    import Title from "$lib/title.svelte"
    import "../styles/global.css"
</script>

<header>
    <Title title="Danyu Gaming Guides" />
</header>

<main>
    <slot />
</main>

<footer>
    <p>Copyright 2022 Chaina Guys Enjoy</p>
</footer>

<style>
    header {
        display: flex;
        justify-content: center;
    }
    main {
        max-width: 960px;
        margin: 20px auto;
    }
    footer {
        text-align: center;
    }
</style>

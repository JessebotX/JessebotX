<script lang="ts">
    import { isActive, url } from "@sveltech/routify";

    const links = [
        [ "./", "home" ],
        [ "games", "games" ],
        [ "projects", "projects" ],
        [ "other-pages", "other pages" ]
    ]
</script>

<nav>
    {#each links as [path, name]}
        <a href={$url(path)} class:active={$isActive(path)}>
            { name }
        </a>
    {/each}
</nav>

<style lang="scss">
    @forward "../scss/components/Nav.scss";
</style>
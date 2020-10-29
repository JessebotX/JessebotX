<script lang="ts">
    import { metatags } from "@sveltech/routify";
    import Header from "../components/Header.svelte";

    metatags.title = "Jessebot";
    metatags.description = "hello...";
    metatags.image = "/favicon.png";
</script>

<Header />

<!-- routify:options index=10 -->
<!-- routify:options title="home" -->

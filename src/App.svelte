<script lang="ts">
  import { Router } from "@sveltech/routify";
  import { routes } from "../.routify/routes";
</script>

<style global lang="scss">
    @forward "scss/index.scss";
</style>

<Router {routes} />

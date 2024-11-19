<script lang="ts">
	import "../app.css";
    import Pages from "../components/template/Pages.svelte";
	let { children } = $props();
</script>

<Pages>
	{@render children()}
</Pages>

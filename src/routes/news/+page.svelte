<script lang="ts">
	import type { PageData } from './$types';

	export let data: PageData;
</script>

<h1>Today's headlines</h1>
{#each data.news as article}
	<h2>{article.title}</h2>
{/each}

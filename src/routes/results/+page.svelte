<script lang="ts">
	import ChannelCard from '$lib/components/ChannelCard.svelte';
	import SearchVideoCard from '$lib/components/SearchVideoCard.svelte';
</script>

<div class="my-2 flex justify-end">
	<button class="rounded-full border px-4 py-1 font-medium hover:bg-gray-200">Filter</button>
</div>
<div class="space-y-5">
	<ChannelCard />
	<SearchVideoCard />
</div>

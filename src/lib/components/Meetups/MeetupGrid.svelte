<script>
	import { meetups } from '$lib/data.js';
	import MeetupItem from '$lib/components/Meetups/MeetupItem.svelte';
</script>

<div class="grid grid-cols-3 gap-4">
	{#each meetups as item (item.id)}
		<MeetupItem
			title={item.title}
			subtitle={item.subtitle}
			description={item.description}
			imageUrl={item.imageUrl}
			address={item.address}
			contactEmail={item.contactEmail}
		/>
	{/each}
</div>

<script>
	export let title;
	export let subtitle;
	export let description;
	export let imageUrl;
	export let address;
	export let contactEmail;

	let showDetails = false;

	function setDetails() {
		showDetails = !showDetails;
	}
</script>

<article class="rounded-md bg-blue-100 p-4 shadow-lg shadow-blue-500/25">
	<header>
		<h1 class="text-2xl font-bold">{title}</h1>
		<h2 class="mb-8 text-blue-100">{subtitle}</h2>
	</header>
	<div>
		<img src={imageUrl} alt="An image of {title}" />
	</div>
	<div>
		<p class="my-4">{description}</p>
	</div>
	<footer>
		<button
			on:click={setDetails}
			class="mr-2 rounded-md bg-blue-700 p-4 text-white hover:bg-blue-950 hover:duration-200"
			>More details</button
		>
		<button class="rounded-md bg-red-500 p-4 text-white hover:bg-red-700 hover:duration-200"
			>Favorite</button
		>
	</footer>
	{#if showDetails}
		<section>
			<h2 class="text-xl font-bold mt-4 mb-4">Details</h2>
			<p>Address: {address}</p>
			<p>Address: {contactEmail}</p>
		</section>
	{/if}
</article>

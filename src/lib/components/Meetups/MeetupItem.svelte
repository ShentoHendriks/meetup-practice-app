<script>
	export let title;
	export let subtitle;
	export let description;
	export let imageUrl;
</script>

<article class="bg-blue-100 p-4 rounded-md shadow-lg shadow-blue-500/25">
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
		<button class="bg-blue-700 text-white p-4 rounded-md mr-2 hover:bg-blue-950 hover:duration-200">Show Details</button>
		<button class="bg-red-500 text-white p-4 rounded-md hover:bg-red-700 hover:duration-200">Favorite</button>
	</footer>
</article>

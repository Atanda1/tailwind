<script>
	export let name;
</script>

<main>
	<div class="container mx-auto border border-indigo-500 px-4">    
		<h1 class="font-bold text-5xl">Photo Gallery</h1>    
		<section class="py-8 px-4">
			<div class="flex flex-wrap mx-4">
				<div class="md:w-1/2 px-4 mb-8 md:mb-0"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
				<div class="md:w-1/2 px-4 mb-8 md:mb-0"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
			</div>
		</section>
							
		<section class="pt-8 px-4">
			<div class="flex flex-wrap mx-4">
				<div class="md:w-1/3 px-4 mb-8"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
				<div class="md:w-1/3 px-4 mb-8"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
				<div class="md:w-1/3 px-4 mb-8"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
				<div class="md:w-1/3 px-4 mb-8"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
				<div class="md:w-1/3 px-4 mb-8"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
				<div class="md:w-1/3 px-4 mb-8"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
			</div>
		</section>
							
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	/* h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	} */

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
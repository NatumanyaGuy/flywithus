<script>
	import Cards from '$lib/Cards.svelte';
	import IconButton from '$lib/IconButton.svelte';
</script>

<div class="flex flex-col lg:flex-row gap-5">
	<div
		class="lg:basis-1/2
		flex flex-col justify-center items-center h-[70vh] md:h-[70vh] lg:h-[70vh] px-2 md:px-4 lg:px-5"
	>
		<div>
			<h1 class="text-6xl md:text-8xl lg:text-8xl font-extrabold">
				COME
				<br />
				FLY WITH US
			</h1>
			<p class="mt-5 text-xl md:text-2xl lg:text-2xl font-bold">
				YOUR MAGICAL EXPERIENCE STARTS HERE
			</p>
		</div>
		<br class="mt-3" />
		<!-- Card  -->
		<div class="lg:hidden md:hidden">
			<Cards _class="" />
		</div>
	</div>

	<div class="basis-1/2 hidden lg:block md:block">
		<div class="w-48 bg-black h-48 top-0 ml-[8rem] hidden md:hidden lg:block fixed" />
		<img src="/air_balloon.png" class="max-h-[77vh] absolute mt-6 z-50" alt="" />

		<br class="mt-3" />
		<!-- Card  -->
		<div class="hidden lg:block md:block">
			<Cards _class="fixed bottom-7" />
		</div>
	</div>
</div>

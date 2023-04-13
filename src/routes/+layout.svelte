<script>
	// @ts-nocheck
	import SideNav from '$lib/SideNav.svelte';
	import TopBar from '$lib/TopBar.svelte';
	import '../app.css';
</script>

<svelte:head />

<div class="lg:hidden md:hidden w-[100vw]">
	<TopBar />
</div>
<div class="flex flex-row gap-4">
	<div class="basis-11/12">
		<slot />
	</div>

	<div class="basis-1/12 fixed right-0">
		<SideNav />
	</div>
</div>

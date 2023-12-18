<script>
	import Searchbar from './Searchbar.svelte';
</script>

<header
	class="sticky left-0 top-0 z-10 flex h-[64px] items-center justify-between border bg-white px-4 py-2"
>
	<a href="/" class="mr-5 md:hidden">
		<img src="/icons/ytLogo.svg" alt="Logo" />
	</a>
	<div class="hidden items-center gap-4 md:flex">
		<img
			src="/icons/burgerIcon.svg"
			class="cursor-pointer rounded-full p-3 hover:bg-gray-200"
			alt="Menu"
		/>
		<a href="/">
			<img src="/icons/ytLogo.svg" alt="Logo" />
		</a>
	</div>

	<Searchbar />

	<div class="hidden items-center gap-3 md:flex">
		<img
			src="/icons/createIcon.svg"
			class="cursor-pointer rounded-full p-3 hover:bg-gray-200"
			alt="Create"
		/>
		<img
			src="/icons/notIcon.svg"
			class="cursor-pointer rounded-full p-3 hover:bg-gray-200"
			alt="Notifications"
		/>
		<img src="/avatar.png" class="h-8 w-8 cursor-pointer rounded-full bg-gray-300" alt="Avatar" />
	</div>
</header>

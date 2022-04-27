<script>
    import NAVITEM from './NavItem.svelte';

	export let open = false
</script>

<aside class="absolute w-200 h-1000 bg-gray-800 border-r-2 shadow-lg" class:open>
	<nav class="p-12 text-xl">
		<a class="block" href="/">Home</a>
		<!-- <a class="block" href="about">About</a>
        <a class="block" href="projects">Projects</a>
		<a class="block" href="team">Team</a>
        <a class="block" href="community">The Community</a>
		<a class="block" href="news">News</a>
        <a class="block" href="contact">Contact</a> -->
	</nav>
</aside>

<style>
	aside {
		right: -100%;
		transition: right 0.1s ease-in-out
	}
	
	.open {
		right: 0
	}
</style>
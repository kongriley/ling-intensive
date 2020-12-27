<script>

	import router from 'page'

	import Home from './views/Home.svelte'
	import Classes from './views/Classes.svelte'
	import Instructors from './views/Instructors.svelte'
	import Signup from './views/Signup.svelte'

	import Link from './components/Link.svelte'

	import Tailwind from './Tailwind.svelte'
	import Navbar from './components/Navbar.svelte'
	
	let page
	
	router('/', () => page = Home)
	router('/classes', () => page = Classes)
	router('/instructors', () => page = Instructors)
	router('/signup', () => page = Signup)
	router.start()

</script>

<style>
</style>

<Tailwind/>

<Navbar/>

<div>
	<svelte:component this={page} />
</div>

<div class="flex justify-center">
	<div class="grid grid-cols-3 divide-x-2 text-center footer mt-16 md:mt-24 mb-10 md:mb-14 w-2/3 text-sm md:text-md lg:text-lg">
		<div>
			<Link href="mailto:lingintensive@gmail.com" text="Email" />
		</div>
		<div>
			<Link href="https://www.instagram.com/ling.intensive/" text="Instagram" />
		</div>
		<div>
			<Link href="https://github.com/kongriley/ling-intensive" text="GitHub" />
		</div>
	</div>
</div>



<script>

	import router from 'page'
	import Home from './views/Home.svelte'
	import Classes from './views/Classes.svelte'
	import Instructors from './views/Instructors.svelte'
	import Signup from './views/Signup.svelte'

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
	<svelte:component this={page}/>
</div>

<template>
  <div id="app">
    <link href="https://fonts.googleapis.com/css?family=Lato:100,300,400,600,700,900" rel="stylesheet">
    <Navbar></Navbar>
    <Home></Home>
    <Features></Features>
    <Prising></Prising>
  </div>
</template>

<script>
	import Navbar from './components/Navbar'
  import Home from './components/Home'
  import Features from './components/Features'
	import Prising from './components/Prising'
 
	export default {
		name: 'App',
		components: {
			Navbar,
      Home,
      Features,
      Prising
		}
	}
</script>


<style>

</style>

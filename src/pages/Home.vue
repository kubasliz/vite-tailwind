<template>
  <main class="w-full h-screen relative">
	  <img id="img" src="/img/beazy.jpg" alt="" class="absolute w-full h-full object-cover">
	
	<header class="relative z-40 w-full h-24 px-12 flex justify-between items-center">
	
		<div class="flex justify-center lg:justify-start">
			<a href="#" class="block w-4 h-2 border-t-2 border-b-2 border-black hover:border-gray-600"></a>
		</div>

		<div class="flex flex-1 lg:justify-center">
			<a href="#" class="font-serif text-2xl block text-center text-black no-underline hover:text-gray-600">Capoeira</a>
		</div>

	</header>	

  </main>

  <div class="w-full py-24 px-6 relative z-10">
		
	  <div class="max-w-4xl mx-auto text-left flex items-center">

		  <div class="w-full">
        <span class="text-gray">Introduction</span>
        <span class="inline-block h-1 w-24 ml-4 border-t border-gray-600"></span>
			  <h1 class="text-2xl text-gray-900 mb-3">Sit id reprehenderit adipisicing elit ad nisi irure ea cillum.</h1>
				  <p class="text-md text-gray-600 leading-normal">
						Quis cupidatat et velit minim laborum magna cupidatat laboris enim sunt fugiat.Ipsum eu aute aliqua incididunt.Culpa aliqua mollit fugiat ut nisi exercitation ut irure.
					</p>

			</div>

			<div class="hidden md:block w-1/3 mr-20">
        <a href="#" class="block w-44 h-44 rounded-full border-2 overflow-hidden">
				  <img src="https://images.unsplash.com/photo-1492567291473-fe3dfc175b45?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=631&q=80" class="w-full h-full object-cover">
				</a>
			</div>
		
    </div>

	</div>

</template>

<script>
import { watchEffect } from 'vue'

export default {
  components: {
  },
  setup () {
    watchEffect(() => {
      console.log('yolo')
    })
    return {}
  }
}
</script>

<style>

  #img {
    clip-path: polygon(100% 0, 100% 83%, 19% 100%, 0 79%, 0 0);
  }

</style>
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
    clip-path: polygon(100% 0, 100% 83%, 19% 101%, 0 79%, 0 0);
  }

</style>
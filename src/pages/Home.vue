<template>
  <main>
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
.home{
  height: 100vh;
}

</style>
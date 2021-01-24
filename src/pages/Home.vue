<template>
  <header class="flex flex-wrap items-center justify-between px-12 h-32">
    <ul class="order-last md:order-first flex-1 flex justify-center md:justify-start list-reset">
				<li>
					<a href="#" class="text-grey-darker no-underline hover:text-black">kuba</a>
				</li>
				<li class="ml-8">
					<a href="#" class="text-grey-darker no-underline hover:text-black">kuba</a>
				</li>
				<li class="ml-8">
					<a href="#" class="text-grey-darker no-underline hover:text-black">kuba</a>
				</li>
			</ul>
	  <div class="flex lg:justify-end">
				<a href="#" class="block w-4 h-2 border-t-2 border-b-2 border-black hover:border-gray-600"></a>
		</div>
  </header>
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
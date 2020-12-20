<template>
  <header class="flex flex-wrap items-center justify-between px-12 h-32">
    <ul class="order-last md:order-first flex-1 flex justify-center md:justify-start list-reset">
				<li>
					<a href="#" class="text-sm text-grey-darker no-underline hover:text-black">kuba</a>
				</li>
				<li class="ml-8">
					<a href="#" class="text-sm text-grey-darker no-underline hover:text-black">kuba</a>
				</li>
				<li class="ml-8">
					<a href="#" class="text-sm text-grey-darker no-underline hover:text-black">kuba</a>
				</li>
			</ul>
  </header>
</template>

<script>
import { onMounted } from 'vue'
import MyHeader from '../components/MyHeader.vue'
export default {
  components: {
    MyHeader
  },
  setup () {
    onMounted(() => {
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
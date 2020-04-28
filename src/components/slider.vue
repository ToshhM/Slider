<template>
<div>
 <vueper-slides class="no-shadow" :slide-ratio="1 / 4">
    <vueper-slide v-for="i in 5" :key="i" :title="i.toString()" :content='slide.content'></vueper-slide>
  </vueper-slides>
</div>
</template>

<script>
import { VueperSlides, VueperSlide } from 'vueperslides'
import 'vueperslides/dist/vueperslides.css'
export default {
    data: () => ({
  slides: [
    {
      title: 'Slide #1',
      content: 'Slide.content'
    }   
  ],
   components: { VueperSlides, VueperSlide },
})

}

</script>

<style>


</style>
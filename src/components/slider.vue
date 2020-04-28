<template>
<div>
 <vueper-slides>
  <vueper-slide v-for="(slide, i) in slides" :key="i" :title="slide.title" :content="slide.content" />
</vueper-slides>
</div>
</template>

<script>
import { VueperSlides, VueperSlide } from 'vueperslides'
import 'vueperslides/dist/vueperslides.css'
export default {
  /*data: () => ({
    
  slides: [
    
    {
      title: 'Slide #1',
      content: 'Slide.content'
    }   
  ],
   
}),*/
data() {
 return {
   slides: [
    {
      title: 'Slide #1',
      content: 'Slide content.'
    }
  ]
 }
},
components: {

     VueperSlides,
     VueperSlide
    
  }

}

</script>

<style>


</style>
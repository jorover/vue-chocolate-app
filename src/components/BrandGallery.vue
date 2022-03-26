<template>

    <BrandData :brands = 'brand' />
  
</template>

<script>

import BrandData from './BrandData.vue'
import imgOne from '../assets/g.jpg'
import imgTwo from '../assets/g0.jpg'
import imgThree from '../assets/g1.jpg'
import imgFour from '../assets/g2.jpg'
import imgFive from '../assets/g3.jpg'
import imgSix from '../assets/g3.jpg'
import imgSeven from '../assets/g2.jpg'
import imgEight from '../assets/g.jpg'
import imgNine from '../assets/g0.jpg'
import imgTen from '../assets/g1.jpg'


export default {

    name: 'BrandGallery',

    data(){
        return {
            brand: []
        }
    },

    components:{
        BrandData
    },

    created () {

        this.brand = [
           {
               id: 1,
               img: imgOne
           },

           {
               id: 2,
               img: imgTwo
           },

           {
               id: 3,
               img: imgThree
           },

           {
               id: 4,
               img: imgFour
           },

           {
               id: 5,
               img: imgFive
           },

           {
               id: 6,
               img: imgSix
           },

           {
               id: 7,
               img: imgSeven
           },

           {
               id: 8,
               img: imgEight
           },

           {
               id: 9,
               img: imgNine
           },

           {
               id: 10,
               img: imgTen
           }

        ]
    }
    

}
</script>

<style>

</style>
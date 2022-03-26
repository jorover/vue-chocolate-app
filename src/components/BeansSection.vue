<template>

    <section class="beansSection my-10">
            <section class="container mx-auto flex beansContent justify-between">
                <aside class="beansImg grid grid-cols-2">
                   <figure :key="image.id" v-for="image of images">
                       <img :src="image.img" alt="#" class="bImg">
                   </figure>
                </aside>   

                <article class="beansText p-7">
                    <h3> The Beans </h3>
                    <h6> QUALITY COCOA FROM AROUND THE GLOBE </h6>
                    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. <br /> Cupiditate, eum temporibus dicta magni dolore accusamus ullam enim ipsam deserunt accusantium ea, culpa modi ipsa doloremque cumque voluptatibus delectus deleniti explicabo?</p>
                    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                    <button class="bg-yellow-400 px-3 py-1 my-3"> GALLERY </button>
                </article>
            </section>

    </section>

  
</template>

<script>

import imgOne from '../assets/c121.jpg'
import imgTwo from '../assets/m.jpg'




export default {
    name: 'Beans',

    data(){
        return {
            images: []
        }
    },

    created(){
        this.images = [
            {
                id: 1, 
                img: imgOne
            },

            {
                id:2,
                img: imgTwo
            }
        ]
    }

}

</script>

<style>

    .beansImg{
        width:50%;
    }
    
    .beansText{
        width: 47%;
    }

    .bImg{
        max-width: 250px;
    }

</style>
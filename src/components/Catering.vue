<template>

    <section class="cateringSection my-10">
        <div class="container mx-auto">
            <section class="cateringContainer flex justify-between">
                <article class="cateringText py-3 my-4">
                    <h3> Catering & Events </h3>
                    <h6> FOR THE SWEETEST MOMENTS IN LIFE </h6>
                    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. <br /> Cupiditate, eum temporibus dicta magni dolore accusamus ullam enim ipsam deserunt accusantium ea, culpa modi ipsa doloremque cumque voluptatibus delectus deleniti explicabo?</p>
                    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. <br /> Cupiditate, eum temporibus dicta magni dolore accusamus ullam enim ipsam deserunt accusantium ea, culpa modi ipsa doloremque cumque voluptatibus delectus deleniti explicabo?</p>
                    <button class="bg-yellow-400 px-3 py-1 my-5"> VIEW SELECTION </button>
                </article>

                <aside class="cateringImg grid grid-cols-3">
                    <figure :key="image.id" v-for="image in images" >
                        <img :src="image.img" alt="#" class="cImg">
                    </figure>

                </aside>
            </section>

        </div>

    </section>
  
</template>

<script>
    import imgOne from '../assets/c.jpeg'
    import imgTwo from '../assets/c1.jpeg'
    import imgThree from '../assets/c10.jpeg'
    import imgFour from '../assets/c11.jpeg'

export default {

    data(){
        return {
            images: []
        }
    },

    created(){
        this.images = [
            {
                id:1, 
                img: imgOne
            },
            
            {
                id:2, 
                img: imgTwo
            },

            {
                id:3, 
                img: imgThree
            },
            
            {
                id:4, 
                img: imgFour
            },

            {
                id:5, 
                img: imgOne
            },
            
            {
                id:6, 
                img: imgTwo
            }


        ]
    }




}
</script>

<style>

    .cateringImg{
        height:fit-content;
    }

    .cImg{
        max-width: 200px;
        height:250px;
        margin:10px;
    }

</style>
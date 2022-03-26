<template>

    <section class="chefSection my-10">
            <section class="container mx-auto flex justify-between chefContent">
                <img :src="chefImg" alt="chef" class="chefImg">
                <article class="chefText p-10">
                    <h3> CaCoa & Me </h3>
                    <h6> MEET CHOCOLATIER MARK CARVALA </h6>
                    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate, eum temporibus dicta magni dolore accusamus ullam enim ipsam deserunt accusantium ea, culpa modi ipsa doloremque cumque voluptatibus delectus deleniti explicabo?</p>
                    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate, eum temporibus dicta magni dolore accusamus ullam enim ipsam deserunt accusantium ea, culpa modi ipsa doloremque cumque voluptatibus delectus deleniti explicabo?</p>
                    <button class="bg-yellow-400 py-2 px-7 m-5"> READ MORE </button>
                </article>
            </section>

    </section>
  
</template>

<script>

import chefImg from '../assets/che.jpg'

export default {

    name: 'Chef',

    data (){
        return {
            chefImg: chefImg
        }
    }

}
</script>

<style>

</style>
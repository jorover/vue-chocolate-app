<template>
            <section class="brandDataSection grid grid-cols-5 gap-3 mx-auto my-10">
                    <figure :key = 'brand.id' v-for="brand of brands" class="brandDataGallery">
                        <img :src="brand.img" alt="images">
                        <button class="brandbtn bg-yellow-400 px-3 py-1 absolute z-10 invisible rounded-lg"> RECIPE </button>
                    </figure>
            </section>
  
</template>

<script>
export default {
    name: 'BrandData',
    props:{
        brands: Array
    }

}
</script>

<style>
        .brandDataGallery{
            transform: scale(1.0);
            transition: 0.5s;
        }
        
        .brandDataGallery:hover{
            transform: scale(1.05);
        }

        .brandDataGallery:hover::after{
            transform: scaleX(1);
             transform-origin: left;
        }
</style>
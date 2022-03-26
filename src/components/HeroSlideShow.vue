<template>

    <div
id="carouselDarkVariant"
  class="carousel slide carousel-fade carousel-dark relative"
  data-bs-ride="carousel"
>

  <!-- Inner -->
  <div class="carousel-inner relative w-full overflow-hidden">
    <!-- Single item -->
    <div class="carousel-item active relative float-left w-full carousel-first-img">
      <div class="carousel-caption md:block absolute text-center p-10">
            <p class="text-white text-1xl">- CHOCOLATE FACTORY -</p>
            <h1 class="text-white text-7xl m-5">
                CHOCOLATES <br />
                de reeves
            </h1>
            <button class="bg-yellow-400 py-2 px-7"> EXPLORE </button>
      </div>
    </div>

    <!-- Single item -->
    <div class="carousel-item relative float-left w-full carousel-second-img">
      <div class="carousel-caption md:block absolute text-center p-10">
        <p class="text-white text-1xl">- CHOCOLATE FACTORY -</p>
            <h1 class="text-white text-7xl m-5">
                CHOCOLATES <br />
                de Bruguni
            </h1>
            <button class="bg-yellow-400 py-2 px-7"> EXPLORE </button>
      </div>
    </div>

    <!-- Single item -->
    <div class="carousel-item relative float-left w-full carousel-third-img">
      <div class="carousel-caption md:block absolute text-center p-10">
          <p class="text-white text-1xl">- CHOCOLATE FACTORY -</p>
        <h1 class="text-white text-7xl m-5">
                CHOCOLATES <br />
                de mercei
            </h1>
            <button class="bg-yellow-400 py-2 px-7"> EXPLORE </button>
      </div>
    </div>
  </div>
  <!-- Inner -->

  <!-- Controls -->
  <button
    class="carousel-control-prev absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline left-0"
    type="button"
    data-bs-target="#carouselDarkVariant"
    data-bs-slide="prev"
  >
    <span class="carousel-control-prev-icon inline-block bg-no-repeat" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button
    class="carousel-control-next absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline right-0"
    type="button"
    data-bs-target="#carouselDarkVariant"
    data-bs-slide="next"
  >
    <span class="carousel-control-next-icon inline-block bg-no-repeat" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
  
</template>

<script>

import imgOne from '../assets/ch1.jpeg'
import imgTwo from '../assets/cc.jpeg'



export default {
    name: 'HeroSlideShow',  
    data(){
        return {
            imgOne: imgOne,
            imgTwo: imgTwo
        }
    }

}
</script>

<style>

</style>
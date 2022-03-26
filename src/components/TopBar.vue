<template>
  <header class="topBar absolute top-0 bg-black text-white">
      <div class="container flex justify-between mx-auto items-center p-5 overflow-hidden">
            <article class="compLogo">
             <h3><span> RC </span></h3>
            </article>

            <nav class="topNav">
              <ul class="mainMenu flex justify-between">
                  <li> HOME </li>
                  <li> MENU </li>
                  <li> ONLINE ORDERING </li>
                  <li>CONTACT US </li>    
              </ul>
            </nav>

            <figure class="socialIcons flex">
                <img :src= "imgOne" />
                <img :src= "imgTwo" />
                <img :src= "imgThree" />
            </figure>

            <aside :class="hamburgerMenus" class="absolute top-5 right-0 text-white z-10">
              <img :src= "imgFour" class="absolute top-0 right-5" @click="hamburgerMenu"/>
              <article class="sideDropMenu bg-black">
                <ul class="mainMenu flex flex-col justify-between py-2">
                  <li> HOME </li>
                  <li> MENU </li>
                  <li> ONLINE ORDERING </li>
                  <li>CONTACT US </li>    
              </ul>
              </article>
            </aside>

    </div>
  </header>
</template>

<script>
    import imgOne from '../assets/fb.png'
    import imgTwo from '../assets/Tw.png'
    import imgThree from '../assets/IG.png'
    import imgFour from '../assets/menu.png'

export default {
  name: 'TopBar',
  data () {
      return {
        imgOne: imgOne,
        imgTwo: imgTwo,
        imgThree: imgThree,
        imgFour: imgFour,
        hamburgerMenus: 'hamburgerMenu'
      }

  },

  methods: {
    hamburgerMenu(){
     if(this.hamburgerMenus === 'hamburgerMenu'){
       this.hamburgerMenus = 'hamburgerMenu openCloseMenu'
     } else {
       this.hamburgerMenus = 'hamburgerMenu'
     }
  } 

  }
}
</script>

<style>


</style>>

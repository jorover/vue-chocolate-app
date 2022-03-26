<template>
    <footer class="footerSection mt-10 bg-yellow-50 p-5">

        <div class="container mx-auto">
            <header class="footercontent">
                <h5 class="text-4xl"> {{ Contact }} </h5>
                <p> {{ info }} </p>
                <p class="underline"></p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br /> Laborum eos libero eum voluptatibus placeat.</p>
            </header>

        <FooterForm />

        </div>

    </footer>
  
</template>

<script>

    import FooterForm from '../components/FooterForm.vue'

export default {
    name: 'Footer',
    data() {
        return {
            Contact: 'Contact Us',
            info: 'info@rc.com / TEL : 231231234'
        }
    },
    components: {
        FooterForm
    }

}
</script>

<style>

</style>
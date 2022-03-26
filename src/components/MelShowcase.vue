<template>
    <section class="showCaseSection">
        <div class="container">
            <article class="showCaseText mx-auto">
                <p class="text-3xl text-center"> <em> " {{ quote }} " </em> <br /> <span class="text-yellow-400"> " Mel Gibson "  </span> </p>
            </article>
        </div>
    </section>
  
</template>

<script>
export default {
    name: 'MelShowCase',
    data(){
        return {
            quote: 'After about 20 years of marriage, I’m finally starting to scratch the surface of that one [what women want]. And I think the answer lies somewhere between conversation and chocolate'
        }
    }

}
</script>

<style scoped>

        .showCaseSection {
            background:url('../assets/m1.jpg') no-repeat center center/cover;
             background-attachment: fixed;

        }

</style>
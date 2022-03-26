<template>
    <section class="showCaseSection">
        <div class="container">
            <article class="showCaseText">
                <p class="text-3xl text-center"> <em> " {{ quote }} " </em> <br /> <span class="text-yellow-400"> " Tom Hanks in Forrest Gump "  </span> </p>
            </article>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Showcase',
    data () {
        return {
            quote: ' Life is like a box of chocolates. You never know what you’re gonna get'
        }
    }

}

</script>

<style scoped>

        .showCaseSection {
            background:url('../assets/dcc.jpg') no-repeat center center/cover;
            background-attachment: fixed;

        }
</style>
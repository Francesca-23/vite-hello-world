<script>

    export default{
        name: "AppHero"
    }

</script>

<template>

    <div>
        <div class="jumbotron jumbotron-fluid">
            <div class="container">
                <p class="lead">This is a modified jumbotron that occupies the entire horizontal space of its parent.</p>
            </div>
        </div>
    </div> 

</template>

<style scoped>
    .jumbotron{
        height: 80vh;
        background-image: url('/images/photo jumbotron.avif');
    }

    p{
        text-align: center;
        font-size: 1.5rem;
        padding-top: 3rem;
    }

</style>
<script>



export default {
    name: 'ComicElements',
    props: [
        'imagePath',
        'comicsPrice',
        'comicsSeries',
        'comicsType'
    ]




}
</script>




<template>





    <div class="comics-elements">
        <img :src="imagePath" alt="image path">
        <h3>{{ comicsSeries }}</h3>
        <div class="price">{{ comicsPrice }}</div>
    </div>


</template>

<style lang="scss" >
.comics-elements {
    color: white;
    width: calc(100% / 6);
    padding: 1rem;


    img {
        width: 100%;
    }

    .price {
        font-size: 12px;
    }

}
</style>

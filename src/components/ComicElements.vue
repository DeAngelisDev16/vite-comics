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
        <!-- {{ imagePath }} -- {{ comicsPrice }} -- {{ comicsSeries }} -- {{ comicsType }} -->
        <img :src="imagePath" alt="image path">
        <h3>{{ comicsSeries }}</h3>
    </div>


</template>

<style lang="scss" scoped>
.comics-elements {
    color: white;
    width: calc(100% / 6);
    padding: 1rem;


    img {
        width: 100%;
    }

}
</style>

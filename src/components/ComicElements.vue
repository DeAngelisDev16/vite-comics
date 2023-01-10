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
    </div>


</template>

<style lang="scss" scoped>
.comics-elements {
    color: white;
    border: 2px solid white;
    width: calc(100% / 6);
    padding: 1rem;

    img {
        width: 100%;
    }

}
</style>

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
        {{ imagePath }} -- {{ comicsPrice }} -- {{ comicsSeries }} -- {{ comicsType }}
    </div>


</template>

<style lang="scss" scoped>
.comics-elements {
    color: white;
    border: 2px solid white;
    width: calc(100% / 6);

}
</style>

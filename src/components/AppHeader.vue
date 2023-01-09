<script>
export default {
    data() {
        return {
            headerNavList: [
                {
                    text: 'Characters'
                },
                {
                    text: 'Comics'
                },
                {
                    text: 'Movies'
                },
                {
                    text: 'TV'
                },
                {
                    text: 'Games'
                },
                {
                    text: 'Collectibles'
                },
                {
                    text: 'Videos'
                },
                {
                    text: 'Fans'
                },
                {
                    text: 'News'
                },
                {
                    text: 'Shop'
                },
            ]
        }
    }
}

</script>

<template>
    <div class="header_wrapper">
        <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li v-for="link in headerNavList">{{ link.text }}</li>
        </ul>
    </div>

</template>

<style lang="scss" scoped>
.header_wrapper {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 1rem;

    img {
        max-width: 100%;
    }

    ul {
        list-style: none;
        display: flex;

        li {
            padding-left: .8rem;
        }
    }
}
</style>
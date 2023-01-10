<script>
export default {

}


</script>

<template>
    <div class="upper_footer">
        <div class="list_wrapper">
            <div class="List one">
                <h2>DC COMICS</h2>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>

                <h2>Shop</h2>
                <ul>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>

            </div>
            <div class="list two">
                <h2>DC</h2>
                <ul>
                    <li><a href="#">Terms of use</a></li>
                    <li><a href="#">Privacy policy (New)</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>

                </ul>
            </div>
            <div class="list three">
                <h2>SITES</h2>
                <ul>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
            </div>











        </div>
    </div>
    <div class="lower_footer"></div>




</template>

<style lang="scss" scoped>
.upper_footer {
    background-image: url('../assets/img/footer-bg.jpg');
}

.lower_footer {
    background-color: #303030;
    height: 20vh;
}

.list_wrapper {
    width: 80%;
    margin: auto;
    padding: 2rem 0;

    display: flex;



    h2 {
        margin-left: 2rem;
        color: white;
    }

    ul {
        margin-left: 2rem;
        list-style: none;

        a {
            text-decoration: none;
            color: #786144;
        }
    }


}
</style>
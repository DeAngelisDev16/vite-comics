<script>
export default {

}


</script>

<template>
    <div class="upper_footer">
        <div class="list_wrapper">
            <div class="row">
                <div class="col">
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
                <div class="col">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>

        </div>

    </div>












    <div class="lower_footer">
        <div class="lower_footer_wrapper">
            <a href="#" id="footer_cta">sign-up now!</a>
            <div class="follow_us">
                <span>follow us</span>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">




            </div>
        </div>
    </div>




</template>

<style lang="scss" scoped>
.upper_footer {
    background-image: url('../assets/img/footer-bg.jpg');



}


.row,
.col {
    display: flex;

    img {
        max-width: 70%;
        margin-left: 2rem;

    }
}



.list_wrapper {
    width: 80%;
    margin: auto;
    padding: 2rem 0;
    display: flex;




    h2 {
        margin: .5rem 2rem;
        color: white;
        padding-top: .5rem;

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




.lower_footer {
    background-color: #303030;

    .lower_footer_wrapper {
        width: 80%;
        margin: auto;
        color: white;
        height: 100%;
        display: flex;
        align-items: center;
        padding: 1rem;
        justify-content: space-between;

        #footer_cta {
            text-decoration: none;
            color: #fff;
            text-transform: uppercase;
            border: 2px solid white;
            padding: .7rem;
        }

        .follow_us {
            display: flex;
            align-items: center;
            padding: 1rem;

            span {
                padding-right: 1rem;
                color: #0381F9;
                text-transform: uppercase;
                font-size: 20px;
            }

            img {
                max-width: 100%;
                padding-right: .7rem;
            }


        }
    }



}
</style>
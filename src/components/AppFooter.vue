<script>
export default {

}
</script>
<template lang="">
    <footer>
        <div class="top-footer">
            <div class="container">
                <div class="top-footer-inner">
                    <div class="top-footer-menu">
                        <h3>dc comics</h3>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                        <h3>shop</h3>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>
                    <div class="top-footer-menu">
                        <h3>dc</h3>
                        <ul>
                            <li><a href="#">Terms of Use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certifications</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="top-footer-menu">
                        <h3>sites</h3>
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
        </div>
        <div class="bottom-footer">

        </div>
    </footer>
</template>
<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.top-footer {
    background-image: url('../img/footer-bg.jpg');
    background-size: cover;

    .top-footer-inner {
        background-image: url('../img/dc-logo-bg.png');
        background-position: right;
        background-repeat: no-repeat;
        display: flex;

        .top-footer-menu {

            padding: 50px 0px;
            margin-right: 30px;

            h3 {
                color: #fff;
                text-transform: uppercase;
            }

            ul {
                list-style-type: none;
                margin: 0px 0px 20px 0px;

                li {
                    padding: 5px 0px;

                    a {
                        color: grey;
                        font-size: 14px;
                    }
                }
            }
        }
    }
}
</style>
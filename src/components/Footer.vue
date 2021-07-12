<template>
    <footer>
        <div class="footer-nav container">
            <nav>
                <div class="list-container">
                    <ul>
                        <li>DC COMICS</li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Video</li>
                        <li>News</li>
                    </ul>
                    <ul>
                        <li>SHOP</li>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
                <div class="list-container">
                    <ul>
                        <li>DC</li>
                        <li>Terms of use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact  us</li>
                    </ul>
                </div>
                <div class="list-container">
                    <ul>
                        <li>SITES</li>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </nav>
            <div class="img-container">
                <img src="../assets/dc-logo-bg.png" alt="dc">
            </div>
        </div>
        <div class="social-fluid-bg">
            <div class="social-footer container">
                <div class="sign-button">SIGN-UP NOW!</div>
                <div class="social-list">
                    <ul>
                        <li>FOLLOW US</li>
                        <li><img src="../assets/footer-facebook.png" alt=""></li>
                        <li><img src="../assets/footer-twitter.png" alt=""></li>
                        <li><img src="../assets/footer-youtube.png" alt=""></li>
                        <li><img src="../assets/footer-pinterest.png" alt=""></li>
                        <li><img src="../assets/footer-periscope.png" alt=""></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name:'Footer'
}
</script>

<style lang="scss" scoped>
    @import "../style/color.scss";
    footer{
        background-image: url(../assets/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        .footer-nav{
            display: flex;
            justify-content: space-between;
            align-items: center;
            nav{
                display: flex;
                padding: 30px 0;
                ul{
                    margin: 0 15px;
                    li{
                        color: $grey-font;
                        margin: 5px 0;
                        font-size: 16px;
                        &:first-child{
                            color: $white-font;
                            margin: 15px 0;
                            font-size: 20px;
                            font-weight: bold;
                        }
                        &:hover{
                            color: $white-font;
                            cursor: pointer;

                        }
                    }
                }
            }
        }
        .social-fluid-bg{
            background: $grey-bg;
            padding: 30px;
            .social-footer{
                display: flex;
                justify-content: space-between;
                .sign-button{
                    padding: 15px;
                    border: 3px solid $blue-color;
                    color: $white-font;
                    font-weight: bold;
                    cursor: pointer;
                }
                .social-list{
                    ul{
                        display: flex;
                        align-items: center;
                        li{
                            padding: 0 15px;
                            cursor: pointer;
                            &:first-child{
                                color: $blue-color;
                                font-size: 24px;
                                font-weight: bold;
                            }
                        }
                    }
                }
            }
        }
    }
</style>
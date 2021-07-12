<template>
    <section>
        <nav class="container">
            <div class="shop-item">
                <img src="../assets/buy-comics-digital-comics.png" alt="comics">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="shop-item">
                <img src="../assets/buy-comics-merchandise.png" alt="merchandise">
                <span>DC MERCHANDISE</span>
            </div>
            <div class="shop-item">
                <img src="../assets/buy-comics-subscriptions.png" alt="subscrription">
                <span>SUBSCRIPTION</span>
            </div>
            <div class="shop-item">
                <img src="../assets/buy-comics-shop-locator.png" alt="shoplocator">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="shop-item">
                <img src="../assets/buy-dc-power-visa.svg" alt="visadc">
                <span>DC POWER VISA</span>
            </div>
        </nav>
    </section>
</template>

<script>
export default {
    name:'BlueBar'
}
</script>

<style lang="scss" scoped>
    @import "../style/color.scss";
    section{
            background: $blue-color;
            padding: 30px 15px;
            nav{
                display: flex;
                justify-content: space-around;
                .shop-item{
                    color: $white-font;
                    display: flex;
                    align-items: center;
                    cursor: pointer;
                    img{
                        height: 50px;
                    }
                    span{
                        margin-left: 15px;
                    }
                }
            }
    }
</style>
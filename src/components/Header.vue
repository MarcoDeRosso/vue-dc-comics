<template>
    <header class="container">
        <div class="logo-container">
            <img src="../assets/dc-logo.png" alt="logo">
        </div>
        <nav>
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name:'Header'
}
</script>

<style lang="scss" scoped>
@import "../style/color.scss";
    header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        nav{
            ul{
                display: flex;
                justify-content: center;
                font-size: 14px;
                font-weight: bold;
                color: $black-font;
                li{
                    height: 125px;
                    line-height: 125px;
                    padding: 0 15px;
                    &:hover{
                        color: $blue-color;
                        cursor: pointer;
                        border-bottom: 5px solid $blue-color;
                    }   
                }
            }
        }
    }
</style>

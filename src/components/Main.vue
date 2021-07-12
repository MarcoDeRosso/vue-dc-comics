<template>
    <main >
        <div class="container">
        Content goes here

        </div>
    </main >
</template>

<script>
    export default {
        name:'Main'
    }
</script>

<style lang="scss" scoped>
    @import "../style/color.scss";
    main{
        background: $black-bg;
        height: 300px;
        color: $white-font;
        display: flex;
        align-items: center;
    }
</style>

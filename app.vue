<template>
    <div class="container">
        <main-header></main-header>
        Hello {{bundler}}
        <body-paragraph content="long form content"></body-paragraph>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Header from "./src/main-header.vue";
import Paragraph from "./src/paragraph.vue";
export default Vue.extend({
    data: () => {
        return {
            bundler: "parcel"
        }
    }
})
</script>

<style lang="scss" scoped>
    @import "./test.scss";
    .container {
        color: cornflowerblue;
    }
</style>

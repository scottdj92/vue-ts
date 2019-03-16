<template>
    <div class="container">
        <main-header></main-header>
        Hello {{bundler}}
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Header from "./src/main-header.vue";
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

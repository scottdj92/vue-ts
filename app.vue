<template>
    <div class="container">Hello {{bundler}}</div>
</template>


<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    data: {
        bundler: "Parcel"
    }
})
</script>

<style lang="scss" scoped>
    .container {
        color: cornflowerblue;
    }
</style>


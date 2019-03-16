<template>
    <div class="container">Hello {{bundler}}</div>
</template>


<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    data() {
        return {
            bundler: "parcel"
        }
    }
})
</script>

<style lang="scss" scoped>
    .container {
        color: cornflowerblue;
    }
</style>


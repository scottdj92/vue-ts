<template>
    <div>
        <p class="body">{{ content }}</p>
        <h4>longer form template</h4>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.component("body-paragraph", {
    props: ["content"]
});
</script>

<style scoped>
    .body {
        color: rebeccapurple;
    }
</style>

<template>
    <div class="page3">
        <p>this is page 3 Root content</p>
        <div>
            <list-view/>
        </div>
        <a href="#/page1">
            Page1
        </a>
        <a href="#/page2">
            Page2
        </a>
    </div>
</template>

<script>

    import ListView from 'vue-list-component-mf-structure'

    export default {
        name: "root",
        components: {
            ListView
        },
        data() {
            return {
                device: null
            }
        },
    }
</script>

<style scoped>
    .page3 a {
        height: 30px;
        width: 50px;
        padding: 5px;
    }
</style>

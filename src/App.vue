<template>
    <div id="app">
        <element-view></element-view>
    </div>
</template>

<script>
    import ElementView from './views/element/ElementView.vue';
    export default {
        components : { ElementView },
        data() {
            return {
                message: "Hello vue 222"
            }
        },
        methods : {

        }
    }
</script>

<style>

</style>

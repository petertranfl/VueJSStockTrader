<template>
    <div class="container-fluid">
        <app-header></app-header>
    </div>
</template>

<script>
    import Header from './components/Header.vue';

    export default {
        components: {
            appHeader: Header
        }
    }
</script>

<style>
    .container-fluid {
        background-color: #f7f7f7;
        margin-top: 70px;
       }
</style>

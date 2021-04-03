<template>
    <div class="container">
        <h1 class="text-center">Ürün Ekleme Uygulaması</h1>
        <hr>
        <app-new-product></app-new-product>
        <br><br>
        <app-progress></app-progress>
        <br><br>
        <app-products></app-products>
    </div>
</template>

<script>
    import NewProduct from "./components/NewProduct";
    import Progress from "./components/Progress";
    import Products from "./components/Products";

    export default {
        components: {
            appNewProduct : NewProduct,
            appProgress : Progress,
            appProducts : Products,
        },

    }
</script>
<style>
    body {
        background-color: aliceblue;
        padding-top: 20px;
        padding-bottom: 20px;
    }

    .card {
        margin-right: 5px;
        margin-bottom: 5px;
    }

    .card:last-child {
        margin-right: 0px;
    }

    .col-md-2 {
        max-width: 15.666667% !important;
    }

    .product-container {
        margin-left: 15px;
    }

</style>

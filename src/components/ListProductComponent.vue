<script setup>
    import CardShoes from './CardSneakersComponent.vue'
</script>


<template>
    <section class="grid-products">
        <CardShoes />
        <CardShoes />
        <CardShoes />
        <CardShoes />
        <CardShoes />
        <CardShoes />
    </section>
</template>


<style scoped>
    .grid-products {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        row-gap: 5px;
        justify-items: center;
        
    }


    /*TODO:Fazer isso depois */
    @media (max-width: 400px) {
        .grid-products {
            display: block;

        }
    }
</style>
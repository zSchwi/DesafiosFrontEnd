<script setup>

</script>

<template>
    <div class="card">
        <div class="card-image">
            <img class="sneaker-image" src="../assets/product1.png" alt="um sneaker verde">
        </div>
        <div class="card-text">
            <p class="sneakers-name">Air Jordan 1 Mid Dutch Green</p>
            <p class="sneakers-category">Tênis Air Jordan</p>
            <div class="purchase-section">
                <p class="sneaker-price">R$ 1.199,99</p>
                <button class="purchase-button">
                    <img src="../assets/carrinho-de-compras.png" />
                    Comprar
                </button>
            </div>
        </div>
    </div>
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300..700&display=swap');

    .card {
        width: 384px;
        height: 326px;
        margin-left: 20px; /*Precisa ser retirado dps*/
    }

    .card-image {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 384px;
        height: 200px;
        background-color: #c4eec9;
        border-radius: 10px 10px 0px 0px;
    }

    .sneaker-image {
        width: 225px;
        height: 135px;
    }
    
    .card-text {
        padding-left: 5px;
    }


    .sneakers-name {
        padding: 10px 0px;
        font-size: 18px;
        font-weight: 600;

    }

    .sneakers-category {
        color: #7CA2F4;
        font-weight: 500;
        font-size: 16px;
        padding-bottom: 12px;

    }

    .purchase-section {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .sneaker-price {
        font-family: "Space Grotesk", sans-serif;
        font-weight: 600;
        font-size: 20px;

        

    }
    .purchase-button {
        display: flex;
        align-items: center;
        gap: 10px;
        font-size: 16px;
        padding: 10px 10px;
        border: none;
        background-color: #9AEBA3;
        border-radius: 5px;
        
    }

</style>
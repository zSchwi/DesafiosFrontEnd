<script setup>
</script>

<template>
    <div class="frete-gratis">
            <p>Frete gratis para todo Brasil</p>
    </div>

    <div class="header-section">
 
        <div class="header-content">
            <div class="logo-section">
                <p class="logo">
                    JordanShoes
                </p>
            </div>
            

            <p class="subtitle">
                A melhor loja de Jordan
            </p>
            <p class="text-description">
                O tênis é fruto de uma velha parceria entre a Nike e o jogador Michael Jordan.
            </p>
        </div>
    </div>
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Archivo:ital,wght@0,100..900;1,100..900&display=swap');

    .header-section{
        width: 100%;
        height: 400px;
        background: linear-gradient(rgba(18, 18, 20, 0.75), rgba(18, 18, 20, 0.75)),
        url('../assets/background-header.png');
        
    }

    .frete-gratis {
        text-align: center;
        font-size: 24px;
        
        font-weight: 500;
        padding: 10px 0;
        
    }

    .header-content {
        width: 557px;
        height: 211px;
        color: #FFFFFF;
        position: relative;
        left: 200px;
        top: 150px;
        

    }

    .logo-section {
        margin-bottom: 20px;
    }

    .logo {
        font-size: 24px;
        
    }

    .subtitle {
        font-size: 32px;
        font-weight: 500;
        margin-bottom: 20px;

    }

    .text-description {
        font-weight: 400;
        font-size: 24px;
        line-height: 33.6px;

    }




</style>
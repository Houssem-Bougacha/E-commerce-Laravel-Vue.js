<template>
    

<section>
            <h2>Bienvenue sur notre site web </h2>
            <div>
    <h3>Découvrez nos produits électroménagers</h3>
    <div class="product-scroll">
        <!-- Ajoutez ici les images de vos produits -->
        <img src="images/four-focus.jpg" alt="Produit 1">
        <img src="images/mo-samsung.jpg" alt="Produit 2">
        <img src="images/mou.jpg" alt="Produit 3">
        <img src="images/mv-candy.jpg" alt="Produit 4">
        <img src="images/oip.jpg" alt="Produit 5">
        <img src="images/ref-samsung.jpg" alt="Produit 6">
        <img src="images/tv.samsung.jpg" alt="Produit 7">
        <!-- Ajoutez autant d'images que nécessaire -->
    </div>
    <a href="http://127.0.0.1:8000/login?#/HomeCart">
        <button>Voir plus d'articles</button>
    </a>
</div>

        </section>

        <footer>
    <p>Suivez-nous sur les réseaux sociaux :</p>
    <a href="https://www.facebook.com/votrepagfacebook" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-facebook social-icon"></i>
    </a>
    <span class="separator">,</span>
    <a href="https://www.instagram.com/votrepageinstagram" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-instagram social-icon"></i>
    </a>
    
</footer>


    
</template>

<script setup>

</script>

<style lang="scss" scoped>
.separator {
        margin: 0 10px; // Ajustez la marge selon vos besoins
        font-size: 1.2em; // Ajustez la taille de la virgule
    }

 section {
        padding: 20px;
        text-align: center;
    }

    footer {
        background-color: #333;
        color: #fff;
        padding: 10px;
        text-align: center;
        position: fixed;
        bottom: 0;
        width: 100%;
    }
    

        div {
            max-width: 800px;
            margin: 90px auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

      
        .product-scroll {
            display: flex;
            overflow-x: auto;
            margin-top: 15px;
        }

        .product-scroll img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            margin-right: 10px;
            border-radius: 8px;
        }

        a button {
            background-color: #4caf50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            text-decoration: none;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }

        a button:hover {
            background-color: #45a049;
        }

</style>
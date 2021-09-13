<template>
<div>
    
    <h1 class="display-1">Liste des objets</h1>
    
    <h2>Objets disponibles</h2>
    <div style="card-deck">
        <div  class="card text-white bg-dark mb-3" style="max-width: 18rem;">
            <div class="card-header"></div>
            <div class="card-body text-white">
                <!-- <p class="card-text">
                    <a href="localhost/5500/posts">Cliquez ici pour consulter les objets disponibles</a>
                </p> -->
            </div>
        </div>
        <p>L'application appel l'API pour afficher les objets avec ses informations.<br>
            Pour consulter les données utiliser postman<br><br><br>
      connexion MongoDB: "mongodb+srv://kelvin:Kmonteiro98@cluster0.yspv3.mongodb.net/troov_test"
        </p>

    </div>

    
</div>
    
</template>
<script>
export  default{
    data(){
        return {
            produits:[
                {nom:"pizza", prix: 3.0},
                {nom:"frites", prix: 2.0},
                {nom:"Hamburger", prix: 2.5},
                {nom:"CheeseBurger", prix: 3.0},
                ]
        }
    }
}

</script>

<style>

</style>

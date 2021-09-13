<template>
<div>
    
    <h1 class="display-1">Inscription</h1>
    
    <h2>Inscription pour l'utilisateur Kelvin avec le mot de passe test123 </h2>
    <div style="card-deck">
        <div  class="card text-white bg-dark mb-3" style="max-width: 18rem;">
            <div class="card-header">Utilisateur: Kelvin</div>
            <div class="card-body text-white">
                <p class="card-text">Mot de passe: test123</p>
                <p class="card-text">Mail: kelvin.fernandes.sio@gmail.com</p>
            </div>
            
        </div>
    </div>

    <a href="http://localhost/5500/posts/register">(l'application appel l'API pour enregistrer les données dans la base de donnée Mongoose)<br>Pour consulter les données utiliser postman<br><br>
      connexion MongoDB: "mongodb+srv://kelvin:Kmonteiro98@cluster0.yspv3.mongodb.net/troov_test"</a>

    
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

<template>
<div>
    
    <h1 class="display-1">Connexion</h1>
    
    <h2>Login et mot de passe pour se connecter</h2>
    <div style="card-deck">
        <div  class="card text-white bg-dark mb-3" style="max-width: 18rem;">
            <div class="card-header">Login: Kelvin</div>
            <div class="card-body text-white">
                <p class="card-text">Mot de passe: test</p>
            </div>
            
        </div>
    </div>

    <a href="localhost/5500/posts/login"> (l'application appel l'API pour accéder au compte de cet utilisateur dans la base de donnée Mongoose)<br>Pour consulter les données utiliser postman<br><br>
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

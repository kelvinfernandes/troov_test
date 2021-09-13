<template>
<div>
    
    <h1 class="display-1">Suppression d'un objet</h1>
    
    <h2>Un objet à supprimer</h2>
    <div style="card-deck">
        <div  class="card text-white bg-dark mb-3" style="max-width: 18rem;">
            <div class="card-header">id: </div>

            
        </div>
    </div>
 


    <a href="localhost/5500/posts/delete/"> (l'application appel l'API pour supprimer l'objet possedant cet id)<br>Pour consulter les données utiliser postman<br><br>
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

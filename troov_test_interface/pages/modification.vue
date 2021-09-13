<template>
<div>
    
    <h1 class="display-1">Modification d'un objet</h1>
    
    <h2>Un objet à modifier</h2>
    <div style="card-deck">
        <div  class="card text-white bg-dark mb-3" style="max-width: 18rem;">
            <div class="card-header">id: </div>
            <div class="card-body text-white">
                <p class="card-text">Lieu où vous avez trouvé l'objet: bibliothèque</p>
            </div>
            
        </div>
    </div>
 
 <h2>Mofication du lieu de  l'objet</h2>
    <div style="card-deck">
        <div  class="card text-white bg-dark mb-3" style="max-width: 18rem;">
            <div class="card-header">id: </div>
            <div class="card-body text-white">
                <p class="card-text">Lieu où vous avez trouvé l'objet: Salle des professeurs</p>
            </div>
            
        </div>
    </div>

    <a href="localhost/5500/posts/update/"> (l'application appel l'API pour modifier le champ lieu de l'objet)<br>Pour consulter les données utiliser postman<br><br>
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

Les-petits-plats-P7
Organisation du projet

Un script principal "script.js" qui s'occupe de la liaison de tous les composants d'affichage, de la récupération des recettes et du tri (c'est le contrôleur de l'app)
Composants
Un composant permettant d'afficher les recettes
Un composant pour les select
Un composant permettant d'afficher le filtre ingrédient / ustensil ou appareil
Helpers: Un utilitaire qui permet de mettre à jour le compteur de recettes
Démo

7/8 minutes de présentation de l'app (hors code) + fiche d'investigation -> Tester les cas aux limites: avec un ingrédient, un ustensil, un appareil et la barre de recherche -> Montrer que les Selects se comportent bien -> Bien montrer que quand on supprime dans la barre de filtre (le truc jaune), les recettes se mettent à jour -> Même si hors périmètre que l'affichage respecte la maquette et est responsive -> + fiche d'investigation
7/8 minutes de présentation de code: -> Présenter l'architecture générale -> Montrer l'organisation du fichier principal script.js avec la fonction init tout en bas -> Parler du filtrage et de la méthodo de filtrage avec filter puis avec for (branche: algo2) -> Quand le switch sur la branche algo2 a été fait, ne pas hésiter à montrer que l'application fonctionne toujours
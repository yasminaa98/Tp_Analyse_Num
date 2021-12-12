# Projet analyse numérique 2021
- [Introduction](#Introduction)
- [Generalité](#Generalité)
- [Les méthodes d'integration numérique](#methodes)
  - [Méthode des Rectangles à gauche](rg)
  - [Méthode des Rectangles à droite](rd)
  - [Méthode des trapézes](t)
  - [Méthode de simpson](s)
- ## Introduction 
- L'intégration est un des problèmes les plus importants que l'on rencontre en analyse. En effet, on rencontre souvent des intégrales dont le calcul par des méthodes analytiques est trés compliqué ou meme impossible, car il n'existe pas d'expression analytique d'une primitive de la fonction à intégrer.
Dans ces cas, on peut appliquer des méthodes composites pour evaluer la valeur de l'integrale donnée. La plupart des méthodes d'intégration numérique fonctionnent sur le même principe. On commence par couper le gros intervalle [a,b] en N plus petits intervalles [ai,ai+1], avec     a1=a et aN+1=b. Puis, pour chaque intervalle [ai,ai+1], on essaie d'approcher .
- ## Generalité
- Si f est une fonction continue sur un intervalle [a,b], bien souvent on ne sait pas calculer une primitive de f. Ainsi, si l'on désire obtenir la valeur de $$\\int_a^b f(t) \\,dt$$ \n , il faut parfois se contenter d'obtenir une valeur approchée à l'aide d'une méthode d'intégration numérique.
  La plupart des méthodes d'intégration numérique fonctionnent sur le même principe. On commence par couper le gros intervalle [a,b] en N plus petits intervalles [ai,ai+1], avec a1=a et aN+1=b. Puis, pour chaque intervalle [ai,ai+1], on essaie d'approcher . Les moyens les plus simples sont :
- ## Les méthodes d'integration numérique
  - Décomposition du domaine en morceaux (un intervalle en sous-intervalles contigus)
  - Intégration approchée de la fonction sur chaque morceau 
  - Sommation des résultats numériques ainsi obtenus.
- ### Méthode des Rectangles à gauche
- ### Méthode des Rectangles à droite
- ### Méthode des trapézes
- ### Méthode de simpson

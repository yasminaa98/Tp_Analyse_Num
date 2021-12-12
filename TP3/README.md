# Projet analyse numérique 2021
- [Introduction](#Introduction)
- [Generalité](#Generalité)
- [Les méthodes d'integration numérique](#Les méthodes d'integration numérique)
  - [Méthode des Rectangles à gauche](#Méthode des Rectangles à gauche)
  - [Méthode des Rectangles à droite](#Méthode des Rectangles à droite)
  - [Méthode du point milieu](#Méthode du point milieu)
  - [Méthode des trapézes](#Méthode des trapézes)
  - [Méthode de simpson](#Méthode de simpson)
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
la méthode des rectangles à gauche : on approche par . Géométriquement, cela signifie qu'on approche l'intégrale de f par l'aire des rectangles hachurés en vert :
- ### Méthode des Rectangles à droite
- ### Methode du point milieu
la méthode du point milieu : on approche par . Géométriquement, cela signifie qu'on approche l'intégrale de f par l'aire des rectangles hachurés en bleu :
- ### Méthode des trapézes
La méthode d'intégration approchée, dite des trapèzes, décrite ci-après, introduite par Newton & Cotes est plus précise que la méthode élémentaire, dite des rectangles, correspondant aux sommes de Cauchy-Riemann, consistant à remplacer la fonction initiale par une approximation en escalier. Graphiquement, sur l'intervalle [xi, xi+1], on remplace l'arc de courbe par le segment [MiNi+1], donc l'aire sous la courbe, par le « rectangle » xi Mi Ni+1 xi+1 (figure de gauche) :
- ### Méthode de simpson
La méthode de Simpson consiste à grouper trois points consécutifs de la courbe Mi, Mi+1 et Mi+2 et de remplacer l'arc de courbe passant par ces trois points par un arc de parabole. Notons que si les points Mi, Mi+1 et Mi+2 sont alignés, le calcul des paramètres de la parabole d'équation y = mx2 + px + q, passant par ces points conduira à m = 0. Par suite, quitte à parler de parabole dégénérée, ce cas n'est pas singulier.

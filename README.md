# Maths Plage
(Cours de mathématiques pour non mathématiciens.)

Ouvrage écrit par :
Léo Bernus et Loïc Chantry, agrégés de mathématiques, docteurs en astrophysique.
Pour compiler totalement : exécuter ```sh compilation.sh```
Pour compiler juste une fois : en raison du paquet ```minted```, il faut compiler avec l'option ```--shell-escape```. Donc, taper :
```pdflatex --shell-escape main.tex```

Structure du fichier
--------------------
```main.tex``` est le fichier compilé.

Le dossier ```broutilles/``` contient les broutilles suivantes :
```titre.tex``` est la page de titre.
```auteurs.tex``` est la page des auteurs.
```image/``` contient toutes les images, rangées par chapitres (sauf le chapitre sur les angles).
Les dossiers ```classicthesis/``` et ```titlesec/``` contiennent des paquets "non officiels". De même pour le fichier ```titlesec.sty```.

```parametres.tex``` contient la liste des paquets ainsi que des commandes utiles.

Les chapitres sont appelés par la commande ```\input{fichier}``` (l'extension n'est pas incluse dans la commande).



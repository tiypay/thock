# THOCK

Endless runner : une bille roule sur un clavier en chocolat. Chaque touche
enfoncee joue un son de switch mecanique. On steer au doigt, on grossit en
ramassant les touches dorees, on saute par-dessus les bombes, on evite les trous.

Jeu web, sans dependance ni build : un seul `index.html` avec son CSS et son JS
en ligne. Rendu 3D fait main sur Canvas 2D (projection perspective + algorithme
du peintre), audio par Web Audio API.

## Lancer en local

Ouvrir `index.html` suffit pour l'essentiel, mais les sons ne se chargeront pas
depuis `file://`. Servir le dossier :

    python -m http.server 8125

puis http://localhost:8125

## Ressources

- `ui/` interface (panneaux, boutons, icones)
- `loading/` visuels des ecrans de chargement
- `sounds/` echantillons de frappe — issus d'une video ASMR YouTube presentee
  comme libre de droits par son auteur
- `music/` musique de menu

## Commandes

Glisser pour diriger, glisser vers le haut pour sauter.

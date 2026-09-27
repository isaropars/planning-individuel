# Sillage

Sept semaines avec le tarot et le parfum pour mettre un projet au monde.
Un parcours © ArcanEssence 2026.

Le site tient dans un seul fichier, `index.html`. Il n'a besoin d'aucun serveur ni d'aucune base de données.

## Mise en ligne sur GitHub Pages

1. Créer un dépôt public nommé `sillage`.
2. Y déposer `index.html` et ce `README.md` avec « Add file », puis « Upload files ».
3. Dans « Settings », ouvrir « Pages ». Choisir « Deploy from a branch », la branche `main` et le dossier `/ (root)`, puis enregistrer.
4. Après une ou deux minutes, le site est en ligne à l'adresse `https://<compte>.github.io/sillage/`.

## Le carnet

Tout ce que la personne écrit s'enregistre dans son navigateur, sur son appareil. Rien ne part sur un serveur. Au module Empreinte, elle peut copier son carnet ou l'enregistrer en fichier texte.

Un carnet commencé sur une adresse ne se retrouve pas sur une autre, ni dans un autre navigateur.

## Les paires de parfums

Les paires ArcanEssence se complètent dans `index.html`, dans l'objet `PAIRES` en tête du script : un parfum accessible et un parfum de niche par module. Tant que les champs restent vides, la page affiche seulement l'accord olfactif de l'arcane.

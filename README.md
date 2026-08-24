# Orva

Carnet de progression pour le roller. Application web personnelle, en un seul fichier.

**→ [Ouvrir l'application](https://maeva-firpionn.github.io/Orva/)**

## Ce que ça fait

- **Objectifs à paliers** : chaque objectif est une suite de paliers à valider, du plus facile au plus dur (sauts, freinages, slides, backward, slalom, figures, cardio).
- **Agenda** : sessions par jour, avec spot, distance, note, photos et vidéos.
- **Progression** : niveau et XP, série de semaines, constance sur 17 semaines, maîtrise par discipline.
- **Distinctions** : six pistes qui montent en paliers (paliers validés, objectifs finis, série, sessions, disciplines, médias).

## Comment ça marche

Un seul fichier `index.html` : HTML, CSS et JavaScript, sans dépendance ni compilation.
Les données (objectifs, sessions, spots, photos, vidéos) sont stockées **localement dans le navigateur** via IndexedDB. Rien n'est envoyé sur un serveur.

Conséquences :

- Les données sont propres à chaque appareil et navigateur, il n'y a pas de synchronisation.
- Pour transférer sa progression : **Réglages → Exporter / Importer** (fichier `.json`).
- Pour un stockage plus durable : ajouter l'app à l'écran d'accueil.

## Installation sur téléphone

Ouvrir le lien, puis « Ajouter à l'écran d'accueil ». L'app s'ouvre alors en plein écran, sans barre de navigateur, et fonctionne hors connexion.

## Technique

Vanilla JS · IndexedDB · GitHub Pages
Polices Anton et Inter. Logo, icônes et photos des spots sont intégrés au fichier.

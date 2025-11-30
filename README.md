                                           ~Trouver le Nombre~

Un jeu interactif de devinette de nombre avec chronomètre, changement de couleurs dynamique et système de niveaux de difficulté.

1) Technologies Utilisées :


HTML5 - Structure de la page

CSS3 - Styles et animations

JavaScript - Logique du jeu et interactions

Git & GitHub - Versionning et hébergement



2) Fonctionnalités Principales :


3 niveaux de difficulté : Facile (1-50), Intermédiaire (1-100), Difficile (1-200)

Chronomètre intégré pour mesurer les performances

Système de feedback visuel : changement de couleur selon la proximité

Indices contextuels : "tu brûles", "tu chauffes", "tu es tiède", "tu es froid"

Enregistrement des records avec localStorage

Design responsive adapté mobile et desktop



3) Lien vers la Page : 
https://ayoub-26.github.io/Ayed_Zambaa_Ayoub_Trouver_le_nombre/


4) Nouveautés Explorées :
   
Gestion de Version avec Git

Commits avec messages descriptifs

Push/Pull pour synchroniser avec le dépôt distant

Hébergement avec GitHub Pages

Déploiement automatique depuis la branche main

Manipulation du DOM et du BOM

Stockage local avec localStorage

5) Difficultés Rencontrées :
   
a) Fonction updatebackground()
Problème : Implémentation du changement progressif de couleur selon la proximité du nombre cible.

Solution :
Calcul dynamique des valeurs RGB basé sur le pourcentage de proximité

b) Enregistrement des Meilleurs Scores
Problème : Persistance des données avec localStorage et gestion des clés uniques par niveau.

Solution :

Création de clés dynamiques : bestTime_${level}

Comparaison et mise à jour conditionnelle des records

c) Gestion des États du Jeu
Problème : Synchronisation entre les différents écrans et réinitialisation des variables.

Solution :

Fonction showScreen() pour gérer la navigation

Réinitialisation complète des compteurs à chaque nouvelle partie

  Solutions Apportées

Débogage systématique avec console.log()

Ressources Utilisées

Stack Overflow pour les problèmes spécifiques

6) Comment Jouer :
   
Choisis un niveau de difficulté

Devine le nombre en entrant des propositions

Utilise les indices

Bats ton record de temps à chaque partie !

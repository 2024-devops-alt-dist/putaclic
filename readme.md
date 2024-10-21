# Projet PutaClic – Version Mexicaine 🎉

![catrina](https://img.freepik.com/fotos-premium/calavera-catrina-retrato-mujer-maquillaje-calavera-azucar-sobre-fondo-flores-rojas_1456-1772.jpg)

## Objectif du projet

Développer un jeu interactif en JavaScript sur le thème mexicain. Le joueur doit cliquer sur des objets culturels (piñatas, calaveras, cactus) apparaissant aléatoirement à l'écran pour marquer des points dans le temps imparti. Le jeu propose trois niveaux de difficulté avec des paramètres différents. Les scores sont sauvegardés, et le meilleur score est mis à jour à chaque nouvelle partie.

![calaveras](https://ar-mag.fr/wp-content/uploads/2019/06/AR47-caladera-mexique-2019.jpg)

---

## Fonctionnalités principales

### 1. Niveaux de difficulté

Le jeu propose 3 niveaux de difficulté thématiques :

-   **¡Chiquito!** (facile)
-   **¡Valiente!** (intermédiaire)
-   **¡Luchador!** (difficile)

Chaque niveau modifie les paramètres suivants :

-   **Nombre d'objets** à apparaître.
-   **Temps de jeu** imparti.
-   **Vitesse de déplacement** des objets.
-   **Temps d’apparition** des objets.

### 2. Système d'objets à cliquer

Les balles sont remplacées par des objets culturels mexicains :

-   **Piñatas** colorées : +1 point.
-   **Calaveras dorées** (crânes en sucre) : +5 points (bonus).
-   **Cactus** : -2 points (malus).

Les objets apparaissent de manière aléatoire à l'écran, se déplacent, et disparaissent après un temps limité.

### 3. Système de score

-   **Score en temps réel** : affiché à l'écran pendant la partie.
-   **Meilleur score** : sauvegardé et mis à jour si le joueur dépasse son ancien record.
-   Les objets bonus et malus influencent directement le score.

### 4. Interface utilisateur

-   **Choix des niveaux** : le joueur peut sélectionner un niveau via une interface thématique mexicaine.
-   **Affichage du temps restant** : un compteur ou une barre de progression montre le temps restant.
-   **Affichage du score** : score actuel visible en temps réel.
-   **Affichage du meilleur score** : toujours visible à côté du score actuel.

### 5. Animation et dynamique

-   Les **piñatas** explosent en **confettis** quand elles sont cliquées.
-   Les **calaveras** dorées produisent un effet lumineux ou des **fleurs de cempasúchil** (fleurs associées à Día de los Muertos).
-   Si un joueur clique sur un **cactus**, des épines apparaissent autour du curseur, symbolisant un malus.

### 6. Musique et sons

-   **Bruitages** : clics sur les objets produisent des sons typiques (maracas, guitare mariachi, etc.).
-   **Musique de fond** : bande sonore mexicaine jouée pendant la partie, intensifiée avec la difficulté.

---

## Technologies utilisées

-   **Langage principal** : JavaScript (utilisation de l'API Canvas pour les animations).
-   **HTML/CSS** : pour l'interface utilisateur (choix des niveaux, affichage des scores).
-   **Local Storage** : pour stocker le meilleur score du joueur.
-   **API Audio** : pour les effets sonores et la musique.

---

## Points techniques

### 1. Génération et animation des objets

-   Les objets (piñatas, calaveras, cactus) sont générés de manière aléatoire sur le canvas et se déplacent à des vitesses variables selon le niveau de difficulté.

### 2. Gestion des événements de clic

-   Les clics sont détectés en fonction des coordonnées des objets. Chaque type d'objet modifie le score en conséquence (bonus, malus, points réguliers).

### 3. Système de timing

-   Un compteur de temps régit la durée de la partie, avec un affichage en temps réel à l'écran.

### 4. Sauvegarde des scores

-   Le meilleur score est sauvegardé localement dans le navigateur du joueur via **Local Storage** et est comparé au score actuel pour être mis à jour.

---

## Étapes de développement

1. **Création de la structure HTML/CSS** pour l'interface utilisateur (choix du niveau, affichage du score).
2. **Développement du système de génération et d'animation** des objets (piñatas, calaveras, cactus).
3. **Ajout des fonctionnalités de clic et de gestion du score** (points, bonus, malus).
4. **Intégration des niveaux de difficulté** avec des paramètres ajustables (vitesse, nombre d'objets, temps).
5. **Implémentation de la sauvegarde du meilleur score** avec Local Storage.
6. **Tests et ajustements** pour équilibrer la difficulté et améliorer l'expérience utilisateur.

---

## Conclusion

Le jeu "PutaClic – Version Mexicaine" offre une expérience immersive en intégrant des éléments culturels mexicains au sein d’un gameplay addictif. Ce projet met en pratique des compétences en JavaScript, gestion d'événements, animations, et stockage local, tout en proposant un design festif et coloré inspiré du Mexique.

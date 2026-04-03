# 👾 [REKT] - Jeux 2D via Unity 3D
-> Projet personnel de jeux vidéo 2D expérimental de type "craft survie" (projet developper afin de mettre en pratique mes apprentissages).

ℹ️ Toutes les ressources utilisées sont personnelles / crées par moi-même

## 🚀 Fonctionnalités et systèmes
[Personnage]
- Déplacements (droite, gauche, saut) fonctionnels et animés.
- Prise en charge de la gravité du personnage.
- Prise en charge d'un inventaire d'items : armes à feu (P90 et m14), outil (pioche), potions - disposant de leurs propres fonctionnalités in-game.
- Possibilité d'équiper les items présents dans l'inventaire dans les mains du personnage pour les utiliser (slot principal).
- Prise en charge des différentes animations propres aux items, lorsqu'ils sont équipés et lors de leur utilisation.                                                                                                                                 -> animations de base adaptées : respiration, course, saut et animations d'utilisations propres : tirs, coup de pioche, ect...
- ATH graphique fonctionnelle et claire -> nombres de ressources (bois, argent, cuivre, champignon) en haut à gauche, inventaire du joueur (8 slots + 1 main hand slot) + barre de vie du personnage en bas.
  
[Environnement]
- Ajout d'une scène intéractive composées d'une multitude de sprites différents : un sol composés de différents type de blocs (terre, pierre, fer, cuivre), des arbres, des points d'eau (lac), d'une cavité abritant des ennemis, d'un marchand d'items, ect..
- Ajout d'un magasin fonctionnel (interface graphique) qui propose à l'achat les items jouables in-game avec un prix différent pour chaque items.
- Ajout d'un système de destruction des éléments du décor (différents blocs composant le sol et le sous sol + arbres) par le joueur dont certains éléments, une fois détruit, augmentent le nombre de ressources dont il dispose.
- Ajout d'ennemis (de type zombie) dotés d'une barre de vie visuel, d'animations d'attaque et de mort, ainsi que de capacité de mouvement lorsque le joueur est detecté dans leur range de detection d'attaque.
- Ajout d'un lance missile pouvant tirés deux types de missiles (animés) : un type de missile qui frappe à des coordonées précises et un autre type qui suit une cible indiquée.
- Ajout d'une interface graphique s'activant lorsque le joueur entre dans la zone de detection autour du lance missile. Elle permet de parametrer le nombre et le type de missile à tirer ainsi que la fréquence des tirs.

## 🛠️ Technologies utilisées
- **Langage :** C#
- **IDE et moteur:** Visual Studio Community 2022 & Unity 3D (Version : Unity 2022.3 LTS (2022.3.62f3)
- **Autres logiciels :** Piksel (pour la création des sprites 2D)
- **OS :** Windows

## 📦 Installation et Lancement
1. Cloner le dépôt : `git clone https://github.com/lucasdelennepro-dev/Rekt-UnityCsharp-2DGame.git`
2. Ouvrir **Unity Hub**.
3. Telecharger la version d'Unity Editor : `Installs` > `Install Editor` > `All` > `Unity 2022.3 LTS (2022.3.62f3)`. 
4. Ouvrir le projet dans Unity Hub : `Projects` > `Add` > `Add project from disk`.
5. Sélectionner le dossier du projet.
6. Lancer le projet `Rekt` dans la fenêtre `project` de Unity Hub.

## 📸 Captures d'écran
![Capture d'écran] (voir la section Captures)

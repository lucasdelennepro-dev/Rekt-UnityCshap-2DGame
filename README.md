# 👾 [REKT] - Jeux 2D via Unity 3D
-> Projet personnel de jeux vidéo 2D expérimental de type "craft survie" (projet developper afin de mettre en pratique mes apprentissages).
(toutes les ressources utilisées sont personnelles / créer par moi-même)

## 🚀 Fonctionnalités et systèmes
[Personnage]
- Déplacements (droite, gauche, saut) fonctionnels et animés.
- Prise en charge de la gravité du personnage.
- Prise en charge d'un inventaire d'items : armes à feu (P90 et m14), outil (pioche), potions - disposant de leurs propres fonctionnalités in-game.
- Possibilité d'équiper les items présents dans l'intentaire dans les mains du personnage afin des les utiliser (slot principal).
- Prise en charge des différentes animations propres aux items, lorsqu'ils sont équipés et lors de leur utilisation (slot principal)
  -> animations de base adaptées : respiration, course, saut et animations d'utilisations propres : tirs, coup de pioche, ect...
- ATH graphique fonctionnelle et claire -> nombres de ressources (bois, argent, cuivre, champignon) en haut à gauche, inventaire (8 slots + 1 main hand slot) et barre de vie du personnage en bas.
[Environnement]
- Ajout d'une scène jouable composées d'une multitude de sprites différents : d'un sol composés de différents type de blocs, des arbres, des points d'eau (lac), d'une cavité habritant des ennemis, d'un marchand, ect..
- Ajout d'un magasin fonctionnel (interface graphique) qui propose à l'achat les items jouables in-game avec un prix différent pour chaque items.
- Ajout d'un système de destruction des éléments du décor (différents blocs composant le sol et le sous sol + arbres) dont certains éléments, après avoir été détruit, augmentent le nombre de ressources dont le joueur dispose.
- Ajout d'ennemis (de type zombie) dotés d'une barre de vie visible, d'animation d'attaque et de mort ainsi que de capacité de mouvement lorsque le joueur est detecté dans leur range de detection d'attaque.
- Ajout d'un lance missile pouvant tirés deux types de missiles animés : un type de missile qui frappe à des coordonées précise et un autre type qui suit une cible indiquée - devant être posé sur le sol après avoir été acheté par le joueur.
- Ajout d'une interface graphique qui s'active lorsque le joueur entre dans la zone de detection autour du lance missile. Elle permet de paramêtrer le nombre et le type de missiles à tirer et la fréquence des tirs.   

## 🛠️ Technologies utilisées
- **Langage :** C# - Unity (Version : Unity 2022.3 LTS (2022.3.62f3))
- **IDE et moteur:** Visual Studio Community 2022 & Unity 3D
- **Autres logiciels :** Piksel (pour la création des sprites 2D)
- **OS :** Windows

## 📦 Installation et Lancement
1. Cloner le dépôt : `git clone https://github.com/lucasdelennepro-dev/Repertoire-Csharp.git`
2. Ouvrir **Visual Studio 2026**.
3. Faire `File` > `Open` > `Project/Solution` > `Existing Projects into Workspace (file .slnx)`.
4. Sélectionner le dossier du projet.
5. Lancer le fichier `Repertoire.slnx`.

## 📸 Captures d'écran
![Capture d'écran] (voir la section Captures)
D

# Virtual Spaghettis (DRAFT)

Attention: ce qui est écrit ici n'est pas forcément encore implémenté.

- [Indications et contre-indications](#Indications)
- [Fonctionnalites](#Fonctionnalites)
- [Utilisation](#Utilisation)
- [Proches Projets](#Connexes)

*Virtual Spaghettis* **exporte des calculs et des patrons imprimables** pour la **découpe de d'éléments linéaires** tels que des barres, planches, fils, spaghettis, etc... en vue de **fabrication d'objets** d'après les **modèles 3D** fournis.

Virtual Spaghettis se décline en deux moutures: 
- une mouture en langage **Python** à utiliser en **ligne de commande** 
- une mouture en **HTML, CSS et JavaScript** pour **navigateur web**

## <a name="Indications"></a>Indications et contre-indications

### Utilisateurs

Virtual Spaghettis devrait s'avérer utile aux étudiants en architecture, architectes, modélistes, maçons, menuisiers et plus généralement à tout artisan de la fabrication avec des objets linéaires droits. 

### Usages

Cet outil est particulièrement utile pour la **fabrication de surfaces réglées**: cônes, conoïdes, cylindres, paraboloïdes hyperboliques, hyperboloïdes à une nappe, hélicoïdes, rubans de Möbius, etc...

Il est aussi adapté à la **fabrication de maillages**. 

Virtual Spaghettis n'est pas adapté à la fabrication de surfaces non-métrées (sphèroïdes, ellipsoïdes, cartes de hauteur, ...). Préférer pour ça *Virtual Millefeuilles*. 

## <a name="Fonctionnalites"></a>Fonctionnalités

### Données calculées

- le **linéaire total** de matériaux à découper, en tenant éventuellement compte de longueurs supplémentaires de fil à attacher avec des nœuds, ou des chutes en cas de découpes en bais de barres ou de planches. 
- Le **linéaire détaillé** des pièces à découper.

### Formats exportés

- csv
- pdf

### Formats importés

- DXF
- DWG
- VRML
- X3D
- POV-Ray

## Origine du projet

Il s'agit d'une re-conception complète d'un projet du début des années 2000, alors réalisé sous forme de Pile HyperCard. J'étais alors étudiant en architecture et trouvait les exercices de fabrication de maquettes de surfaces métrées un peu trop facile. J'avais donc créé un simple formulaire dans lequel entrer les équations paramétriques de deux courbes 3D, et un programme enfantin calculant et affichant à l'échelle les longueurs calculées pas à pas entre ces deux courbes. Il suffisait alors d'imprimer la vue à l'écran pour obtenir un patron à l'échelle des longueurs de spaghettis à découper pour fabriquer la maquette de la surface 3D ainsi .

Par définition, cette méthode ne permettait que de créer des maquettes de surfaces métrées. Maintenant, avec cette version


###

###

## <a name="Utilisation"></a>Utilisation

1. **Sélection d'une source** de données 3D à importer
2. **Interprétation Géométrique** de la source choisie
3. **Export** d'un imprimable

### 1. Sélection d'un source

#### Version HTML

#### Version Python

### 2. Interprétation Géométrique de la source choisie

#### Version HTML

#### Version Python

### 3. Export d'un imprimable

#### Version HTML

#### Version Python

## <a name="Connexes"></a>Proches Projets

### Virtual Origamis

*Virtual Origamis* est un développement de *Virtual Spaghettis* pour produire des patrons de pliages d'après modèles 3D et non plus seulement des maillages. 

### Virtual Millefeuille

*Virtual Millefeuilles* est un projet similaire qui produit des patrons de collages stratifiés d'après modèles 3D. 


<a name="indications">Indications</a>
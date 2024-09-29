##  Mise en œuvre du principe Ouvert / Fermé
### Énoncé d'exercice : Calculateur d'aire pour des formes géométriques

Vous devez concevoir une application en Java qui permet de calculer l'aire de différentes formes géométriques (cercle, rectangle, triangle, etc.). Actuellement, vous devez gérer uniquement les cercles et les rectangles. Cependant, il est important que votre système soit conçu de telle manière que l'ajout de nouvelles formes (comme le triangle ou le carré) ne nécessite pas de modification des classes existantes.

#### Contraintes :

 - **Appliquez le principe ouvert / fermé (OCP)** : Le système doit être **ouvert à l'extension** (vous devez pouvoir ajouter de nouvelles formes géométriques facilement) mais **fermé à la modification** (vous ne devez pas modifier le code des formes existantes pour ajouter de nouvelles formes).
 - Créez une structure qui permet de définir facilement de nouvelles formes géométriques avec leur propre logique de calcul d'aire.

#### Liste des opérations à exécuter une fois le projet terminé: 

 1. Créer une liste qui regroupera les formes géométriques
 2. Ajouter des formes variées dans cette dernière
 3. Itérer sur la liste et pour chaque forme, afficher son aire dans la console

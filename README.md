# Gestion de Stock sur Excel

Ce projet consiste en un système de gestion des stocks développé sous Microsoft Excel. Il permet de suivre et de gérer efficacement les niveaux de stock, les entrées et sorties de produits, ainsi que les réapprovisionnements.

## Fonctionnalités

- Suivi en temps réel des niveaux de stock
- Gestion des réapprovisionnements
- Analyse des mouvements de stock

## Formules Utilisées

1. **Stock Final** : 
   Stock Final = Stock Initial + [Entrée - Sortie]

2. **Valeur du Stock** : 
   Valeur du Stock = Stock Final * Prix Unitaire (PU)

3. **Montant du Stock** : 
   Montant du Stock = Somme des Valeurs du Stock

## Éléments Utilisés

Pour la mise en place du projet, les éléments suivants ont été utilisés :

- **Liste déroulante** : Pour sélectionner le code des articles
- **RECHERCHEX()** : Pour rechercher la désignation de l'article en fonction de son code
- **SIERREUR()** : Pour gérer les erreurs lors des recherches
- **SOMME.SI()** : Pour calculer les totaux conditionnels
- **Mise en forme conditionnelle** : Pour visualiser les niveaux de stock critiques
- **SI.CONDITION** : Pour établir des règles logiques dans les calculs

## Conclusion

Ce projet est conçu pour aider les petites et moyennes entreprises à améliorer leur gestion des stocks et à optimiser leurs processus opérationnels. N'hésitez pas à explorer le fichier Excel pour découvrir toutes ses fonctionnalités !

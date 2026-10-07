# Fiche de Situation Professionnelle - Application de Gestion C#

## 1. Contexte et Objectifs
Dans le cadre de la formation BTS SIO, il a été demandé de réaliser une application de gestion avec le langage C#. Le choix du sujet était libre, avec comme contrainte technique la simulation d'une base de données via la lecture et l'écriture dans un fichier texte (`.txt`).
J'ai choisi de développer **Neptune's Device Manager**, une application de gestion d'appareils connectés (type domotique).

## 2. Compétences mobilisées (Référentiel SLAM)
- **B2.1 Concevoir et développer une solution applicative** : Création de l'interface graphique sous Windows Forms et développement de la logique applicative en C#.
- **B2.3 Gérer les données** : Mise en place de fonctions de sérialisation personnalisées pour enregistrer les objets dans un fichier texte avec séparateurs (`.txt`).

## 3. Technologies et Outils
- **Langage :** C# (.NET)
- **Interface :** Windows Forms
- **Stockage :** Fichier Texte structuré
- **IDE :** Rider (JetBrains)

## 4. Déroulement et Tâches réalisées
1. **Conception de l'Interface Graphique** : Création d'un tableau de bord permettant l'ajout, la modification, la suppression et le listage en temps réel des appareils.
2. **Programmation Orientée Objet (POO)** : Création d'une classe métier `Appareil` pour structurer les données (ID, Nom, Type, Pièce).
3. **Persistance des données (CRUD)** :
   - *Create* : Écriture d'une nouvelle ligne dans le fichier avec un ID généré aléatoirement.
   - *Read* : Lecture du fichier ligne par ligne pour remplir une liste dynamique.
   - *Update / Delete* : Manipulation du fichier pour retirer ou modifier des lignes ciblées via leur ID.

## 5. Limites et Axes d'Améliorations
S'agissant d'un exercice d'apprentissage, certaines limites sont présentes :
- Aucune vérification stricte contre les doublons d'ID aléatoires.
- Les champs de texte ne se réinitialisent pas automatiquement après une action.
- Pas de base de données relationnelle (SQL), ce qui limite les performances sur un grand volume de données.

## 6. Preuves associées
Consultez le dossier `Preuves/` pour visualiser les extraits de code commentés illustrant la logique C# (Logique Métier et Événementielle).

# FICHE DE SITUATION PROFESSIONNELLE (ÉPREUVE E4)

## 1. IDENTIFICATION GÉNÉRALE
- **Titre de la réalisation :** Neptune's Device Manager (Application de Gestion C#)
- **Cadre de réalisation :** [ ] Stage 1  [ ] Stage 2  [ ] Atelier de professionnalisation  [x] Projet de cours
- **Période de réalisation :** [À compléter]
- **Modalité :** [x] Individuel  [ ] En équipe (préciser le nombre de collaborateurs)
- **Localisation / Organisation cliente :** Deltacube / Projet de formation BTS SIO

## 2. CONTEXTE ET OBJECTIFS
- **Contexte organisationnel :** Dans le cadre de la formation BTS SIO (Spécialité SLAM), un projet libre devait être mené en langage C# afin d'aborder les interfaces graphiques et la manipulation de données.
- **Problématique / Besoin exprimé :** Développer un système complet (CRUD) simulant une base de données sans SGBD complexe, en utilisant uniquement la lecture/écriture dans un fichier texte.
- **Objectifs fixés :** Obtenir une application fonctionnelle de gestion d'appareils connectés (ajout, suppression, modification, listage temps réel) respectant la séparation logique/interface.

## 3. DÉMARCHE ET ENVIRONNEMENT TECHNIQUE
- **Environnement technologique mobilisé :**
  - Langage de développement : C# (.NET)
  - Interface graphique : Windows Forms
  - IDE : Rider (JetBrains)
  - Stockage : Fichier Texte (.txt structuré avec délimiteurs '|')
- **Démarche suivie étape par étape :**
  1. Conception de l'interface graphique (Dashboard, champs texte, ComboBox).
  2. Programmation Orientée Objet : Création de la classe Appareil avec ses attributs et méthodes de persistance (Save(), GetAll()).
  3. Liaisons événementielles : Développement du code behind (Form1.cs) pour lier les boutons aux actions métiers.
  4. Tests de validation des données dans le fichier Appareils.txt.
- **Gestion des imprévus / Incidents rencontrés :** [À compléter, ex: difficulté avec la lecture des lignes vides ou formatage des TextBox]

## 4. RÔLE ET CONTRIBUTION PERSONNELLE
- **Responsabilité précise :** Développeur full-stack du projet (Conception globale, dev C#, tests).
- **Actions menées individuellement :** Réalisation complète du code source, design de l'interface, gestion de la sérialisation personnalisée.

## 5. LIVRABLES ET PREUVES ASSOCIÉES
*(Éléments vérifiables intégrés sur le portfolio)*
- Interface de l'application (Captures d'écran)
- Extraits de code C# commentés (Classe métier et code interface)
- Extrait du fichier de stockage Appareils.txt
- Code source complet disponible sur le repository Projet_CSharp_BTS_SIO_Application_Gestion

## 6. COMPÉTENCES SLAM MOBILISÉES

### Bloc 1 : Support et mise à disposition de services informatiques
- [ ] **B1.1 Gérer le patrimoine informatique :** 
- [ ] **B1.2 Répondre aux incidents et demandes d'assistance :** 
- [ ] **B1.3 Développer la présence en ligne :** 
- [ ] **B1.4 Travailler en mode projet :** 
- [ ] **B1.5 Mettre à disposition des utilisateurs un service informatique :** 
- [ ] **B1.6 Organiser son développement professionnel :** 

### Bloc 2 : Conception et développement d'applications (SLAM)
- [x] **B2.1 Concevoir et développer une solution applicative :** Création de l'interface graphique sous Windows Forms et développement de la logique métier C#.
- [ ] **B2.2 Assurer la maintenance corrective ou évolutive d'une solution applicative :** 
- [x] **B2.3 Gérer les données :** Mise en place de fonctions de sérialisation pour enregistrer et lire les objets dans un fichier texte avec séparateurs.

### Bloc 3 : Cybersécurité des services informatiques
- [ ] **B3.1 Protéger les données à caractère personnel :** 
- [ ] **B3.2 Préserver l'identité numérique de l'organisation :** 
- [ ] **B3.3 Sécuriser les équipements et les usages des utilisateurs :** 
- [ ] **B3.4 Garantir la disponibilité, l'intégrité et la confidentialité :** 

## 7. BILAN RÉFLEXIF ET AUTO-ÉVALUATION
- **Points forts :** Séparation nette entre le code de l'interface (Form) et le code métier (Classe).
- **Axes d'amélioration :** Manque d'une vérification d'unicité sur les ID générés aléatoirement et d'un tri sur la ListBox de l'interface. SGBD type MySQL ou SQLite préférable à un fichier .txt.
- **Compétences professionnelles consolidées :** Assimilation des fondamentaux de la POO en C#, gestion événementielle d'une application de bureau.

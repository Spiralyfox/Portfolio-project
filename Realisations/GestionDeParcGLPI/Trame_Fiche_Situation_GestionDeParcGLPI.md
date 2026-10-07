# FICHE DE SITUATION PROFESSIONNELLE (ÉPREUVE E4)

## 1. IDENTIFICATION GÉNÉRALE
- **Titre de la réalisation :** Déploiement, Inventaire et Support via GLPI
- **Cadre de réalisation :** [ ] Stage 1  [ ] Stage 2  [ ] Atelier de professionnalisation  [x] Projet de cours
- **Période de réalisation :** Décembre 2025 (Semestre 1 - BTS SIO)
- **Modalité :** [x] Individuel  [ ] En équipe
- **Localisation / Organisation cliente :** BTS SIO

## 2. CONTEXTE ET OBJECTIFS
- **Contexte organisationnel :** La gestion du patrimoine informatique et l'assistance aux utilisateurs sont les piliers des services informatiques (Bloc 1). 
- **Problématique / Besoin exprimé :** Comment recenser efficacement un parc informatique de plus de 200 machines et gérer les demandes d'assistance des utilisateurs de manière centralisée et tracée ?
- **Objectifs fixés :** Prendre en main la solution open source GLPI pour réaliser un inventaire (manuel puis automatisé via agent) et paramétrer un module complet d'assistance (Helpdesk).

## 3. DÉMARCHE ET ENVIRONNEMENT TECHNIQUE
- **Environnement technologique mobilisé :**
  - Application : GLPI (Gestionnaire Libre de Parc Informatique)
  - Modules : Agent GLPI (Remontée automatique), Helpdesk (Ticketing)
- **Démarche suivie étape par étape :**
  1. Paramétrage initial : Création des lieux, statuts, et fabricants.
  2. Inventaire : Saisie manuelle de matériels avec plan de nommage, suivie du déploiement de l'Agent GLPI pour automatiser la remontée logicielle et matérielle.
  3. Paramétrage logiciel : Gestion des licences et règles de dictionnaires pour filtrer les remontées.
  4. Centre de services : Création d'utilisateurs avec des profils adaptés (Technicien, Observateur, Self-Service) et simulation de résolution d'incidents via l'outil de ticketing.
- **Gestion des imprévus / Incidents rencontrés :** Le "bruit" généré par la remontée automatique des logiciels (nombreux composants Windows inutiles à inventorier) a été résolu en appliquant des règles d'exclusion dans le dictionnaire GLPI.

## 4. RÔLE ET CONTRIBUTION PERSONNELLE
- **Responsabilité précise :** Administrateur du système GLPI lors de l'exercice.
- **Actions menées individuellement :** Configuration complète des entités, déploiement simulé de l'agent, et endossement de tous les rôles lors des scénarios de ticketing.

## 5. LIVRABLES ET PREUVES ASSOCIÉES
- Comptes-rendus des Travaux Pratiques (TP1 à TP3) résumés dans le dossier Preuves/.
- Capture d'écran de l'interface et page de présentation complète sur mon portfolio web.

## 6. COMPÉTENCES SLAM MOBILISÉES

### Bloc 1 : Support et mise à disposition de services informatiques
- [x] **B1.1 Gérer le patrimoine informatique :** Recensement des postes, gestion des licences logicielles, et déploiement de l'inventaire automatisé (Agent).
- [x] **B1.2 Répondre aux incidents et demandes d'assistance :** Traitement de tickets d'incident, priorisation et communication avec les utilisateurs simulés.
- [ ] **B1.3 Développer la présence en ligne :** 
- [ ] **B1.4 Travailler en mode projet :** 
- [x] **B1.5 Mettre à disposition des utilisateurs un service informatique :** Mise en place et configuration du portail Helpdesk (Self-Service) pour la déclaration des incidents.
- [ ] **B1.6 Organiser son développement professionnel :** 

### Bloc 2 : Conception et développement d'applications (SLAM)
- [ ] **B2.1 Concevoir et développer une solution applicative :** 
- [ ] **B2.2 Assurer la maintenance corrective ou évolutive d'une solution applicative :** 
- [ ] **B2.3 Gérer les données :** 

### Bloc 3 : Cybersécurité des services informatiques
- [ ] **B3.1 Protéger les données à caractère personnel :** 
- [ ] **B3.2 Préserver l'identité numérique de l'organisation :** 
- [ ] **B3.3 Sécuriser les équipements et les usages des utilisateurs :** 
- [ ] **B3.4 Garantir la disponibilité, l'intégrité et la confidentialité :** 

## 7. BILAN RÉFLEXIF ET AUTO-ÉVALUATION
- **Points forts :** La transition réussie entre un inventaire manuel lourd et un inventaire automatisé par agent, démontrant l'intérêt de l'outil pour les grandes infrastructures.
- **Axes d'amélioration :** Le projet est resté au stade de l'exercice. Une vraie implémentation sur un réseau d'entreprise permettrait d'approfondir le déploiement de l'agent par GPO.
- **Compétences professionnelles consolidées :** Assimilation parfaite du processus de ticketing (ITIL) et de la rigueur nécessaire dans la gestion des actifs logiciels (conformité des licences).

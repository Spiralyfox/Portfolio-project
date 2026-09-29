# 🗺️ Cartographie des Projets & Matrice des Savoirs SIO

Ce document permet de positionner chaque réalisation (Ateliers de professionnalisation, TP, stages) au sein du référentiel BTS SIO et de préparer le tableau de synthèse officiel de l'épreuve **E4 (Support et mise à disposition de services informatiques)**.

---

## 1. Cartographie Visuelle (Mermaid)

```mermaid
mindmap
  root((Projets & Réalisations<br/>BTS SIO))
    %% BLOC 1 - TRONC COMMUN
    (Bloc 1 - Support & Services<br/>Tronc Commun - Épreuve E4)
      ["1.1 Patrimoine"]
        Projet Inventaire & CMDB : GLPI [S1]
        Gestion des droits & annuaires : AD, LDAP [S2]
        PCA / PRA & Tolérance aux pannes [S3]
        Sauvegardes & Restauration : Borg, scripts [S4]
        Gestion des licences & charte info [S5]
      ["1.2 Incidents & Assistance"]
        Helpdesk, ticketing & démarches ITIL [S6]
        Diagnostic causal & résolution de panne [S7]
        Réseaux de base & adressage IP [S8]
        Systèmes d'exploitation & virtualisation [S9]
        Scripting système : Bash, PowerShell [S10]
        Engagements contractuels SLA / GTR [S11]
      ["1.3 Présence en Ligne"]
        Développement Web, CMS & SEO [S12]
        Cadre légal Web, RGPD & noms de domaine [S13]
      ["1.4 Mode Projet"]
        Méthodes prédictives vs agiles Scrum [S14]
        Suivi de projet, tickets & calcul d'écarts [S15]
      ["1.5 Déploiement de Services"]
        Architecture de service & déploiement [S16]
        Tests d'acceptation, intégration & recette [S17]
      ["1.6 Développement Professionnel"]
        Veille informationnelle & identité pro [S18]
        Portfolio d'ingénierie & traçabilité Git
    %% BLOC 2 - SISR
    (Bloc 2 - Option SISR<br/>Infrastructures Réseaux - Épreuve E5)
      ["Conception Réseau"]
        Segmentation : VLANs, routage inter-VLAN
        Haute disponibilité : VRRP, agrégation
      ["Déploiement Système"]
        Contrôleur de domaine, DNS, DHCP
        Hyperviseurs Proxmox/VMware, Linux/Windows
      ["Supervision & Exploitation"]
        Supervision réseau : Zabbix, métrologie
        Automatisation & configuration : Ansible
    %% BLOC 2 - SLAM
    (Bloc 2 - Option SLAM<br/>Solutions Applicatives - Épreuve E5)
      ["Conception & Modélisation"]
        Cahier des charges, diagrammes UML / Merise
        Patrons d'architecture : modèle MVC
      ["Développement & Frameworks"]
        Applications Web, API REST & frameworks
        Clients mobiles ou lourds
        Chaîne d'intégration continue CI/CD
      ["Gestion des Données"]
        Bases de données SQL, MariaDB, PostgreSQL
        Persistance des données & ORM
    %% BLOC 3 - CYBERSÉCURITÉ
    (Bloc 3 - Cybersécurité<br/>Transversal - Épreuve E6)
      ["Socle Commun Cyber"]
        Protection des données & conformité RGPD
        Authentification forte MFA & moindres privilèges
        Centralisation des journaux (logs) & preuve
      ["Cyber SISR"]
        Durcissement, pare-feu réseau, DMZ, IDS/IPS
      ["Cyber SLAM"]
        Sécurisation du code (OWASP), tokens & sessions

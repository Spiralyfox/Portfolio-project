# 🎓 BTS SIO — Parcours d'Ingénierie & Suivi de Compétences

Bienvenue sur le dépôt de suivi de formation du **BTS Services Informatiques aux Organisations (RNCP Niveau 5)**.

Ce dépôt sert d'outil de pilotage personnel tout au long des deux années de formation. Il fait le pont entre vos réalisations techniques (TP, projets, stages) et les exigences de certification des épreuves nationales.

---

## 📌 Présentation de la formation

Le BTS SIO prépare aux métiers des infrastructures réseaux, du développement applicatif et de la cybersécurité.

* **Tronc commun (Semestre 1) :** Socle technique, méthodologique et de support.
* **Choix de l'option (dès le Semestre 2) :**
  * **Option SISR** (*Solutions d'Infrastructure, Systèmes et Réseaux*) : administration de serveurs, routage, virtualisation, supervision et haute disponibilité.
  * **Option SLAM** (*Solutions Logicielles et Applications Métiers*) : modélisation, frameworks de développement, bases de données, architectures web et mobiles.
* **Cybersécurité transversale :** Présente sur l'ensemble du cursus pour garantir la disponibilité, l'intégrité, la confidentialité et la conformité légale (RGPD) des services.

---

## 🗺️ Cartographie des Blocs et Réalisations

Le diagramme ci-dessous illustre l'articulation entre vos activités en laboratoire / stage et les trois blocs constitutifs du diplôme :

```mermaid
mindmap
  root((Projets BTS SIO))
    (Bloc 1 - Support & Services<br/>Tronc Commun - Épreuve E4)
      ["Gestion du Patrimoine"]
        Inventaire & CMDB : GLPI
        Sauvegardes & Continuité : PRA, scripts
        Habilitations & Droits : Annuaire AD, LDAP
      ["Assistance & Incidents"]
        Ticketing & Helpdesk : ITIL
        Diagnostic de pannes : Analyse causale
      ["Mise à disposition & Projets"]
        Conteneurisation : Docker
        Méthodes Agiles : Scrum, Kanban
      ["Développement Pro"]
        Veille informationnelle & cyber
        Portfolio d'ingénierie & Git
    (Bloc 2 - Spécialité SISR ou SLAM<br/>Épreuve E5)
      ["Option SISR"]
        Segmentation réseau : VLAN, routage
        Services réseau : DNS, DHCP, AD
        Supervision & Métrologie : alertes, sondes
        Scripting système : Bash, PowerShell
      ["Option SLAM"]
        Modélisation : UML, Merise
        Développement & Frameworks : MVC, API REST
        Persistance : SQL, MariaDB, ORM
        DevOps : CI/CD, tests automatisés
    (Bloc 3 - Cybersécurité<br/>Transversal - Épreuve E6)
      ["Socle Commun Cyber"]
        Protection des données : RGPD, chiffrement
        Contrôle d'accès : MFA, moindres privilèges
        Traçabilité : Centralisation des logs, audit
      ["Spécialité Cyber"]
        Durcissement & Pare-feu SISR
        Sécurisation applicative SLAM : OWASP

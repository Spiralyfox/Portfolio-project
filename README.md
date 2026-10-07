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
  root((Projets et Realisations<br/>BTS SIO))
    (Bloc 1 - Support et Services<br/>Tronc Commun - Epreuve E5)
      ["1.1 Patrimoine"]
        ["Projet Inventaire et CMDB : GLPI (S1)"]
        ["Gestion des droits et annuaires : AD, LDAP (S2)"]
        ["PCA / PRA et Tolerance aux pannes (S3)"]
        ["Sauvegardes et Restauration : Borg, scripts (S4)"]
        ["Gestion des licences et charte info (S5)"]
      ["1.2 Incidents et Assistance"]
        ["Helpdesk, ticketing et demarches ITIL (S6)"]
        ["Diagnostic causal et resolution de panne (S7)"]
        ["Reseaux de base et adressage IP (S8)"]
        ["Systemes d exploitation et virtualisation (S9)"]
        ["Scripting systeme : Bash, PowerShell (S10)"]
        ["Engagements contractuels SLA / GTR (S11)"]
      ["1.3 Presence en Ligne"]
        ["Developpement Web, CMS et SEO (S12)"]
        ["Cadre legal Web, RGPD et noms de domaine (S13)"]
      ["1.4 Mode Projet"]
        ["Methodes predictives vs agiles Scrum (S14)"]
        ["Suivi de projet, tickets et calcul d ecarts (S15)"]
      ["1.5 Deploiement de Services"]
        ["Architecture de service et deploiement (S16)"]
        ["Tests d acceptation, integration et recette (S17)"]
      ["1.6 Developpement Professionnel"]
        ["Veille informationnelle et identite pro (S18)"]
        ["Portfolio d ingenierie et tracabilite Git"]
    (Bloc 2 - SISR<br/>Infrastructures Reseaux - Epreuve E5)
      ["Conception Reseau"]
        ["Segmentation : VLANs, routage inter-VLAN"]
        ["Haute disponibilite : VRRP, agregation"]
      ["Deploiement Systeme"]
        ["Controleur de domaine, DNS, DHCP"]
        ["Hyperviseurs Proxmox/VMware, Linux/Windows"]
      ["Supervision et Exploitation"]
        ["Supervision reseau : Zabbix, metrologie"]
        ["Automatisation et configuration : Ansible"]
    (Bloc 2 - SLAM<br/>Solutions Applicatives - Epreuve E5)
      ["Conception et Modelisation"]
        ["Cahier des charges, diagrammes UML / Merise"]
        ["Patrons d architecture : modele MVC"]
      ["Developpement et Frameworks"]
        ["Applications Web, API REST et frameworks"]
        ["Clients mobiles ou lourds"]
        ["Chaine d integration continue CI/CD"]
      ["Gestion des Donnees"]
        ["Bases de donnees SQL, MariaDB, PostgreSQL"]
        ["Persistance des donnees et ORM"]
    (Bloc 3 - Cybersecurite<br/>Transversal - Epreuve E6)
      ["Socle Commun Cyber"]
        ["Protection des donnees et conformite RGPD"]
        ["Authentification forte MFA et moindres privileges"]
        ["Centralisation des journaux logs et preuve"]
      ["Cyber SISR"]
        ["Durcissement, pare-feu reseau, DMZ, IDS/IPS"]
      ["Cyber SLAM"]
        ["Securisation du code OWASP, tokens et sessions"]

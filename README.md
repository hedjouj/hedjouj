## Elhadj Messaoui

Alternant chargé de la cybersécurité · objectif consultant cybersécurité

Dans une PME industrielle (~220 salariés, 8 sites en France), je construis la sécurité du SI à partir de zéro : gouvernance, durcissement, visibilité et détection. Je garde un pied dans l'administration systèmes et réseaux, parce qu'on ne sécurise bien que ce qu'on connaît de l'intérieur.

En parallèle, je prépare le titre professionnel Administrateur d'Infrastructures Sécurisées (niveau 6).

### Ce que je mets en place

- **Gouvernance** : analyse de risques EBIOS Risk Manager, PSSI, charte informatique
- **Détection** : PoC SIEM Wazuh avec remontée des logs Active Directory, FortiGate, NAS et Microsoft 365, règles de détection et playbooks de réponse
- **Gestion de crise** : plan de réponse à incident, fiches réflexes (rançongiciel, compromission de compte privilégié, fuite de données), exercice sur table
- **Sécurité produit** : sécurisation des équipements connectés et de l'application client de l'entreprise

### Ce que j'ai déjà livré

- **Visibilité sur l'infra** : reprise d'une supervision arrêtée depuis 3 mois (21 hôtes morts, des milliers d'alertes ignorées). Résultat : 34 hôtes, 95 contrôles utiles, alertes lisibles et bilan quotidien. L'inventaire a révélé une cause de pannes à répétition (un DNS obsolète depuis 2 ans), des disques au bord de la saturation et un mot de passe stocké en clair.
- **Messagerie** : DMARC, scan-to-email des copieurs passé en OAuth 2.0 (Entra ID) sur tous les sites
- **Moindre privilège** : retrait des droits admin locaux par GPO, refonte des ACL sur plus de 230 dossiers utilisateurs (NAS Synology)
- **Projet de certification** : architecture multi-sites sécurisée (lien FAI redondé, refonte PKI/VPN, bastion Guacamole, journalisation centralisée)

### Stack

**Sécurité** : Wazuh, FortiGate, OpenVPN, nftables, EBIOS RM
**Supervision** : Nagios, Checkmk
**Systèmes** : Debian, Windows Server, Active Directory (Windows et Samba 4), Hyper-V, VMware
**Microsoft 365** : Entra ID, Exchange Online, SharePoint Online
**Scripts** : Bash, PowerShell, Python

### Le cap

Aujourd'hui, poser les fondations de la cybersécurité d'une entreprise réelle. Demain, accompagner d'autres organisations en tant que consultant.


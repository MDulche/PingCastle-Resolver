# Description du projet / Project Description


## English
This project involves a comprehensive security audit of an Active Directory environment using the PingCastle tool, followed by systematic implementation of remediation recommendations.  
The goal is to address organizational, technical, and operational weaknesses identified during the audit, to achieve a security level compliant with ANSSI standards and best practices from Microsoft.

The work is structured around several key areas:  
- **Inventory and vulnerability analysis**: Each detected issue (obsolete protocols, excessive privileges, password management practices, insufficient auditing, etc.) is documented, explained, and prioritized.  
- **Automated remediation**: For each point, precise PowerShell commands are proposed to automate corrections (GPO, UNC path hardening, disabling risky services, privileged account management, etc.).  
- **Verification and validation**: For each action, a technical verification procedure is provided to ensure effectiveness and compliance.  
- **Operational context considerations**: Recommendations take into account business constraints, application dependencies, and real-world environment specifics (e.g., inability to upgrade all machines to Windows 11, maintaining certain services).  
- **Documentation and traceability**: The entire process, technical choices, and commands are documented to ensure reproducibility and facilitate knowledge transfer.

**Important note**: A dedicated file is provided for each Windows Server version to tailor the recommendations accordingly.

This project has been carried out with perplexity.ai.


## Français
Ce projet consiste en un audit approfondi de la sécurité d’un environnement Active Directory à l’aide de l’outil PingCastle, suivi de la mise en œuvre systématique des recommandations de remédiation.  
L’objectif est de corriger les faiblesses organisationnelles, techniques et opérationnelles identifiées, afin d’atteindre un niveau de sécurité conforme aux référentiels ANSSI et aux bonnes pratiques Microsoft.

Le travail s’articule autour de plusieurs axes :  
- **Inventaire et analyse des vulnérabilités** : Chaque problème détecté (protocoles obsolètes, droits excessifs, mauvaises pratiques de gestion des mots de passe, audit insuffisant, etc.) est documenté, expliqué et priorisé.  
- **Remédiation automatisée** : Pour chaque point, des commandes PowerShell précises sont proposées afin d’automatiser la correction (GPO, durcissement des chemins UNC, désactivation de services à risque, gestion des comptes privilégiés, etc.).  
- **Vérification et validation** : Pour chaque action, une procédure de vérification technique est fournie pour s’assurer de l’efficacité de la mesure et de la conformité de l’environnement.  
- **Prise en compte du contexte opérationnel** : Les recommandations tiennent compte des contraintes métiers, des dépendances applicatives et des réalités du parc (ex : impossibilité de migrer tous les postes vers Windows 11, maintien de certains services).  
- **Documentation et traçabilité** : L’ensemble de la démarche, des choix techniques et des commandes utilisées est documenté pour garantir la reproductibilité et faciliter le transfert de compétences.

Ce projet s’inscrit dans une démarche d’amélioration continue de la sécurité Active Directory, en s’appuyant sur des outils d’audit reconnus, des référentiels institutionnels, et des méthodes éprouvées d’automatisation et de contrôle.

**Note importante** : Un fichier spécifique est fourni pour chaque version de Windows Server afin d’adapter les recommandations à votre environnement.

Ce travail a été réalisé avec perplexity.ai.


## Sources / Sources

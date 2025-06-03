# Active Directory Security Hardening Guide  
**Guide de durcissement de la sécurité Active Directory**  

---

## ⚠️ Legal Notice / Avis juridique  
This repository is not affiliated with PingCastle. The proposed solutions are based on generic best practices and not PingCastle reports.  
[Official PingCastle Website](https://www.pingcastle.com)  

Ce dépôt n'est pas affilié à PingCastle. Les solutions proposées sont basées sur des bonnes pratiques génériques.  
[Site officiel PingCastle](https://www.pingcastle.com)  

---

## Project Description / Description du projet  

### English
This project provides a **systematic methodology** for securing Active Directory environments through:  
1. Vulnerability assessment using industry-standard tools  
2. Automated remediation via PowerShell scripts  
3. Compliance validation with ANSSI/Microsoft benchmarks  

**Key Features**  
- Windows Server version-specific configurations (2012R2 to 2022)  
- MITRE ATT&CK mitigation mapping  
- Operational constraint considerations  

Developed with [Perplexity AI](https://www.perplexity.ai) for technical analysis.  

### Français
Ce projet propose une **méthodologie systématique** pour sécuriser les environnements Active Directory :  
1. Évaluation des vulnérabilités avec outils standards  
2. Correction automatisée via scripts PowerShell  
3. Validation de conformité ANSSI/Microsoft  

**Caractéristiques**  
- Configurations spécifiques par version Windows Server  
- Cartographie des atténuations MITRE ATT&CK  
- Prise en compte des contraintes opérationnelles  

Développé avec [Perplexity AI](https://www.perplexity.ai) pour l'analyse technique.  

---

## Structure / Structure  

### [Nom du Problème]  
*(ex : Délégation Kerberos non protégée)*  


#### Explication du Problème / Problem Explanation  
Brève description technique du risque (ex : Permet des attaques DCSync via délégation de compte administrateur).  
**Impact / Impact** : Description succincte des conséquences (ex : compromission totale du domaine).  


#### Raisons potentielles de non-résolution / Possible Reasons for Non-Resolution  
1. Erreur de syntaxe dans les commandes PowerShell / Syntax error in PowerShell commands  
2. Droits insuffisants de l'utilisateur exécutant le script / Insufficient permissions of the executing user  
3. Réplication AD non terminée entre contrôleurs / AD replication not completed across domain controllers  


#### Solution proposée / Proposed Solution  
- Commandes PowerShell / PowerShell commands  
- Recommandations / Recommendations  
- Explication de la solution / Explanation of the solution  

---

## Sources / Sources  
| Resource | Lien |
|----------|------|
| ANSSI Guide | [PDF](https://www.ssi.gouv.fr/uploads/2015/03/NT_Active_Directory_Configuration_Recommendations.pdf) |  
| Microsoft Security Baselines | [Docs](https://learn.microsoft.com/fr-fr/windows/security/operating-system-security/security-baselines) |  
| CIS Benchmarks | [Windows Server](https://www.cisecurity.org/benchmark/microsoft_windows_server) |  
| PingCastle Methodology | [White Paper](https://www.pingcastle.com/documentation/) |  

---

## Contribution Guidelines / Contribution  
1. Fork the repository  
2. Create feature branches (`git checkout -b feature/improvement`)  
3. Follow PowerShell scripting standards (PSScriptAnalyzer)  
4. Submit Pull Request with detailed description  

*All contributions must comply with [Non-Profit OSL 3.0](https://github.com/vletoux/pingcastle/blob/master/LICENSE.md)*  

---

## License / Licence  
[![License: Non-Profit OSL 3.0](https://img.shields.io/badge/License-Non--Profit%20OSL%203.0-lightgrey.svg)](https://opensource.org/licenses/NPOSL-3.0)  

**Commercial use prohibited** - See [PingCastle EULA](https://www.pingcastle.com/terms-and-conditions/) for auditing services.  

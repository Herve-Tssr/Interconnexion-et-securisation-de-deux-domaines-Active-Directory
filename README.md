# Active-Directory-Lab-Security-Migration
Simulation d’une infrastructure Active Directory : audit de sécurité, analyse des vulnérabilités et migration vers Windows Server 2019.

---

![Windows Server](https://img.shields.io/badge/Windows%20Server-2016%20→%202019-blue)
![Active Directory](https://img.shields.io/badge/Active%20Directory-Lab-lightgrey)
![Security](https://img.shields.io/badge/Security-Audit-red)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

---

## 🧠 Contexte

Projet réalisé dans le cadre de ma formation TSSR, simulant une infrastructure Active Directory en environnement entreprise.

Objectif : analyser, sécuriser et faire évoluer un contrôleur de domaine.

---

## 🎯 Objectifs

- Mettre en place un environnement Active Directory  
- Réaliser un audit de sécurité  
- Identifier et corriger les vulnérabilités  
- Préparer et effectuer une migration vers Windows Server 2019  

---

## 🧩 Étapes du projet

| Étape | Description |
|------|------------|
| 🔍 Audit | Analyse de sécurité avec PingCastle |
| 🛠️ Préparation | Vérification et sécurisation de l’environnement |
| 🔄 Migration | Passage de Windows Server 2016 à 2019 |

---

## 📊 Audit – Résumé

> **Domain Risk Level : 100 / 100**

Analyse réalisée avec PingCastle en mode privilégié.

### Principales vulnérabilités :

- 🔥 MS17-010 (EternalBlue)  
- 🔥 SMBv1 / NTLMv1 actifs  
- 🔥 Print Spooler actif sur le DC  
- ⚠️ LLMNR activé  
- ⚠️ Absence de LAPS  

👉 Détail : `/01-Audit`

---

## 🛠️ Approche

Les vulnérabilités ont été classées selon leur impact :

- 🔥 Critique → risque direct  
- ⚠️ Important → mauvaise pratique  
- 🧪 Mineur → optimisation  

Objectif : prioriser les actions de correction avant migration.

---

## 🔎 Points d’apprentissage

Ce projet m’a permis de consolider plusieurs compétences :

- Structuration des accès avec la méthode AGDLP  
- Diagnostic et résolution de problèmes réseau  
- Configuration du pare-feu Windows  
- Analyse de vulnérabilités dans un environnement Active Directory   

---

## 🧰 Outils utilisés

- Active Directory (AD DS)  
- DNS  
- PowerShell  
- PingCastle  

---

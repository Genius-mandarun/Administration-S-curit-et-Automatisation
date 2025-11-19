# 🛡️ Sécurité des Comptes & Utilisateurs sur Linux

Analyse, durcissement et gestion sécurisée des utilisateurs — Projet de portfolio en cybersécurité & administration système.

Badges :  
`Linux Security` • `Bash Scripting` • `User Management`

## 📝 Résumé du projet

Ce projet a pour objectif de sécuriser en profondeur la gestion des comptes et utilisateurs sur un système Linux.

Il suit une méthodologie :

- Analyse du système  
- Configuration propre  
- Durcissement avancé  
- Automatisation par scripts  
- Rapport final  

Le projet démontre : administration Linux, gestion permissions, ACL, SUID/SGID, audits Bash, documentation technique.

## 📁 Structure du projet

```
security-users-management-linux/
│
├── README.md
│
├── 01-analyse/
│   ├── utilisateurs.md
│   ├── groupes.md
│   ├── permissions.md
│   └── suid-sgid-sticky.md
│
├── 02-configuration/
│   ├── creation-utilisateurs.md
│   ├── creation-groupes.md
│   ├── organisation-home.md
│   └── gestion-sudoers.md
│
├── 03-securisation/
│   ├── politiques-mots-de-passe.md
│   ├── verrouillage-comptes.md
│   ├── acl.md
│   └── reduction-suid.md
│
├── 04-scripts/
│   ├── audit-utilisateurs.sh
│   ├── audit-groupes.sh
│   └── audit-permissions.sh
│
└── 05-rapport/
    ├── rapport-final.pdf
    └── recommandations.md
```

## 🎯 Objectifs principaux

### 🧩 Objectifs techniques

- Analyse comptes / groupes / permissions  
- Organisation du système  
- Permissions sécurisées  
- ACL  
- Politique mots de passe  
- Réduction SUID/SGID  
- Scripts d’audit  

### 👨‍💻 Compétences démontrées

Linux administration, permissions, ACL, sudo hardening, Bash scripting, audits, documentation technique.

## 🚀 Plan complet

### 1️⃣ Analyse — `01-analyse/`

- Lister utilisateurs, shells  
- Analyser groupes  
- Vérifier /home  
- SUID/SGID/sticky  
- Audit auth.log  

### 2️⃣ Configuration — `02-configuration/`

- Création d’utilisateurs et groupes  
- Organisation /home  
- sudoers strict  

### 3️⃣ Sécurisation — `03-securisation/`

- chage  
- Verrouillage comptes  
- ACL  
- Réduction SUID/SGID  

### 4️⃣ Scripts — `04-scripts/`

Exécution :

```bash
chmod +x 04-scripts/audit-utilisateurs.sh
sudo ./04-scripts/audit-utilisateurs.sh
```

### 5️⃣ Rapport — `05-rapport/`

Contexte, analyse, vulnérabilités, mesures, recommandations.

## 🧰 Technologies

| Domaine | Outils |
|--------|--------|
| Admin Linux | useradd, usermod, passwd, chage |
| Permissions | chmod, chown, setfacl, getfacl |
| Audit | journalctl, last, who, grep, find |
| Automatisation | Bash |
| Documentation | Markdown, PDF |

## 👤 Auteur

> Projet réalisé par **Gracia Mboma**.  



# 1. Introduction

Cette section présente l’analyse complète des utilisateurs présents sur le système Linux.
L’objectif est d’obtenir une vision précise de l’ensemble des comptes configurés, de leur rôle et de leur niveau d’accès.

Cette analyse constitue la première étape du processus de sécurisation, car une mauvaise gestion des comptes utilisateurs représente l’une des principales sources de vulnérabilités dans un environnement Linux.

# 2. Objectifs de l’analyse
L’analyse des utilisateurs a pour objectifs :
- d’identifier les différents types de comptes (administrateur, utilisateurs humains, comptes systèmes, services) ;
- d’examiner les informations essentielles comme l’identifiant unique (UID) et le shell associé ;
- de mettre en évidence les comptes pouvant se connecter au système ;
- de repérer les comptes inactifs, suspects ou nécessitant une action ;
- de préparer les actions de durcissement qui seront réalisées dans les étapes suivantes.

Ces éléments servent de base pour établir un état des lieux fiable avant d’appliquer les politiques de sécurité.

# 3. Étapes de l’analyse
L’analyse des utilisateurs se déroule en plusieurs étapes logiques :

Étape 1 – Recensement des utilisateurs enregistrés

Collecter la liste complète des comptes déclarés sur le système afin d’identifier tous les utilisateurs existants et leur rôle potentiel.

Étape 2 – Identification des comptes humains et comptes systèmes

Analyser les identifiants (UID) pour distinguer les utilisateurs réels, les comptes administrateurs et les comptes systèmes utilisés par des services internes.

Étape 3 – Vérification des shells associés aux comptes

Déterminer lesquels disposent d’un shell interactif leur permettant d'ouvrir une session, afin de repérer d’éventuels accès inutiles ou risqués.

Étape 4 – Analyse de l’état des comptes

Examiner l’activation, la désactivation ou le verrouillage de chaque compte afin de détecter les comptes inactifs, obsolètes ou vulnérables.
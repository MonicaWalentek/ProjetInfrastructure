# Projet Infrastructure

Ce projet est un projet donné par le CESI développé sur **Ubuntu**.

## Description du projet

Notre client, ici le CESI, a besoin d’une infrastructure réseau comprenant un serveur de pré-production ainsi qu’un serveur de production. Il a besoin d’un CMS que nous choisirons pour représenter son activité, et voudrait également un espace personnel pour chacun de ses collaborateurs et développeurs leur permettant de personnaliser leurs pages web et de les rendre accessibles au public.

## Objectifs atteints :

- Mise en place d'un serveur web de pré-production sur un système Linux
- Installer les modules nécessaires et les configurer
- Configurer des accès SSH pour permettre l’ajout de contenu via un client SFTP
- Créer une base de données et installer un CMS (Wordpress dans notre cas)
- Automatiser la création et la suppression de nouveaux utilisateurs ainsi que leurs dossiers personnels pour le développement
- Mettre en place un serveur web de production pour pouvoir migrer le contenu développé et le rendre accessible
- Configurer des accès SSH entre la pré-production et la production pour permettre la migration de façon sécurisée
- Sécuriser l’accès au contenu de chaque serveur via un certificat SSL
- Migrer le contenu depuis le serveur de pré-production et programmer des back-ups de la base de données

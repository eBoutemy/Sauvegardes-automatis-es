# Backup Script pour le Serveur Apache

Ce script automatise le processus de création de sauvegardes des données du serveur Apache et les copie de manière sécurisée vers un serveur distant via SSH.

Prérequis

Avant d'utiliser ce script, assurez-vous que les éléments suivants sont en place :

- Un serveur exécutant Apache (`apache2`).
- Un accès SSH au serveur de sauvegarde distant (`backup@172.16.208.72`).
- Vous disposez des privilèges `sudo` pour installer des packages et exécuter des commandes.

Installation et Configuration

Suivez ces étapes pour configurer le script de sauvegarde sur votre serveur :

1. **Installer Apache2** (si ce n'est pas déjà fait) :
   ```bash
   sudo apt-get install apache2 -y

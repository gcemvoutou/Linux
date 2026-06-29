# 🛠️ Infrastructure de Sauvegarde Réseau sous Linux

Ce projet présente la mise en place complète d'une architecture de sauvegarde centralisée, sécurisée et redondante entre deux machines virtuelles Ubuntu[cite: 2].

## 🚀 Fonctionnalités implémentées

* **Architecture Client/Serveur NFS** : Configuration et sécurisation d'un partage réseau natif Linux pour centraliser le stockage des données[cite: 2].
* **Sauvegarde Chiffrée (Duplicati)** : Déploiement et planification de sauvegardes incrémentielles automatisées avec un chiffrement fort AES-256[cite: 2].
* **Redondance en Ligne de Commande (CLI)** : Manipulation, exportation et isolation des volumes chiffrés à l'aide des outils natifs `cp` et `tar`[cite: 2].
* **Automatisation Système** : Planification de tâches d'archivage en arrière-plan via le gestionnaire `crontab`[cite: 2].

## 📂 Technologies utilisées

* **Système d'exploitation** : Ubuntu Linux
* **Protocole réseau** : NFS (Network File System)
* **Logiciels & Outils** : Duplicati, Crontab, Tar, Bash

---

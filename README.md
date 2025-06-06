# Simulation-Configuration-D-un-R-seau-SOHO
# 🏢 Projet Réseau SOHO – Novatech Solutions

Ce projet simule la **conception, la configuration et la sécurisation d’un réseau SOHO (Small Office/Home Office)** pour une entreprise fictive appelée **Novatech Solutions**, à l’aide de **Cisco Packet Tracer**. Il aborde les principes essentiels d’un réseau professionnel, de la couche physique à la couche réseau, en passant par la sécurité et la redondance.
![image](https://github.com/user-attachments/assets/2538367a-997c-4311-8d60-5a72339820aa)

---

## 🗂️ Sommaire

- [📖 À propos du projet](#-à-propos-du-projet)
- [🧰 Prérequis](#-prérequis)
- [🧩 Architecture réseau](#-architecture-réseau)
- [📖 Détail de la configuration](#détail-de-la-configuration)
- [🎯 Objectifs](#-objectifs)
- [📌 Statut du projet](#-statut-du-projet)
- [📬 Contact](#-contact)

---

## 📖 À propos du projet

Le projet est divisé en deux grandes phases :

- **Phase 1 – Conception de la topologie** :
  - Choix des équipements
  - Plan d’adressage IP
  - Répartition logique du réseau
  - Présentation de la topologie finale

- **Phase 2 – Configuration des équipements** :
  - Ajout de modules
  - Configuration de base des appareils (hostname, IP, etc.)
  - Mise en œuvre de **VTP**, **trunks**, **EtherChannel (LACP)**
  - Activation de **Spanning Tree (STP / Rapid PVST+)**
  - Implémentation du **HSRP**
  - Configuration de la **sécurité des ports** (Port Security Sticky)
  - Routage statique et vérifications de connectivité

---

## 🧰 Prérequis

Avant d’exécuter ou d’ouvrir le projet, assurez-vous d’avoir :

- ✅ [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) (version 8.x ou ultérieure)
- ✅ Une connaissance de base en réseau (adressage IP, VLANs, commutation, routage)
- ✅ (Facultatif) Un éditeur de texte (VS Code, Notepad++…) pour consulter les commandes sauvegardées

---

## 🧩 Architecture réseau

- Routeurs Cisco
- Switches L2 et L3
- Répartition hiérarchique (core / distribution / accès)
- VLANs pour la segmentation du réseau
- Adressage structuré par sous-réseaux
- Protocoles actifs :  
  - **STP / Rapid PVST+**  
  - **HSRP (redondance)**  
  - **EtherChannel (LACP)**  
  - **VTP (gestion des VLANs)**  
  - **Port Security + BPDU Guard**

---

## 📖 Détail de la configuration

Chaque équipement a été configuré étape par étape avec :

- 🔐 Configuration de sécurité (enable secret, mot de passe console et VTY)
- 🌐 Affectation des VLANs et interfaces
- 🔄 Trunks et EtherChannel
- 🛡️ STP, BPDU Guard, HSRP
- 🧪 Commandes de vérification et de test

Les configurations sont accompagnées de **captures d’écran** pour chaque appareil.

---


## 🎯 Objectifs 

- Mettre en pratique les connaissances en réseaux Cisco
- Concevoir un réseau stable, sécurisé et redondant
- Comprendre les interactions entre les couches 2 et 3
- Réaliser des tests de connectivité, de sécurité et de basculement

---

## 📌 Statut du projet

✅ **Projet terminé**  
📁 Fichiers Packet Tracer et documentation inclus

---

## 📬 Contact

Réalisé par **EL-GAOUT ZINEB**  
🎓 Étudiante en 1ère année cycle ingénieur , Génie Informatique – ENSA Kénitra  
📧 Email : elgaoutzineb3@gmail.com  
🔗 LinkedIn  : [https://www.linkedin.com/in/zineb-el-gaout-4086a432a?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B%2BW4gm8HtSQW6pFqknZZj%2Fw%3D%3D]

---

> 📝 *Ce projet a été réalisé dans un cadre académique pour simuler un réseau d’entreprise fiable et conforme aux bonnes pratiques Cisco.*

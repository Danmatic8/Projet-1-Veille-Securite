# Projet 1 : Mise en place d'une Veille en Cybersécurité
Mise en place d'un système de veille et d'analyse de menaces pour une entreprise du secteur de l'énergie

**Contexte :** Projet réalisé dans le cadre du Bootcamp Cybersécurité.
**Scénario :** Analyste SOC stagiaire chez *Altergize*, une entreprise du secteur de l'énergie (Entité Essentielle NIS 2).
**Date de réalisation :** Décembre 2025

---

## 🎯 Objectifs de la mission

* Organiser un système de veille active sur des menaces spécifiques (Secteur Énergie & Technologies critiques).
* Identifier les vulnérabilités pertinentes pour l'infrastructure de l'entreprise.
* Produire un rapport d'aide à la décision pour la direction (RSSI).

## 🏢 Périmètre surveillé (Scope)

* **Secteur :** Énergie Verte (Production & Distribution).
* **Géographie :** France (ANSSI), USA (CISA), Royaume-Uni (NCSC).
* **Technologies critiques identifiées :**
    * 📡 **Fortinet FortiOS (VPN)** : Point d'entrée accès distants.
    * 📂 **MOVEit Transfer** : Échange de données sensibles.
    * 🖥️ **Windows Server 2012 R2 & Windows 7** : Gestion de la dette technique (Obsolescence).

## 🚨 Résultats clés (Semaine du 11 Décembre 2025)

Ce rapport a permis de lever deux alertes critiques nécessitant une action immédiate de la direction :

1.  **Alerte Critique Fortinet (CVE-2025-59718)** : Identification d'une faille de contournement d'authentification publiée le 09/12/2025.
    * *Action recommandée :* Patching sous 24h du pare-feu périmétrique.
2.  **Menace Active MOVEit (CVE-2025-10932)** : Détection de campagnes de ransomwares (Groupe Cl0p) exploitant une faille d'octobre 2025.
    * *Action recommandée :* Mise à jour prioritaire du serveur de fichiers.

## ⚖️ Analyse Réglementaire

* **Directive NIS 2 :** Mise en évidence des obligations de reporting (24h) pour Altergize en tant qu'Entité Essentielle.
* **ISO 27001:2022 :** Analyse de l'écart (Gap Analysis) entre la version 2013 et 2022 concernant la sécurité du Cloud et la gestion des vulnérabilités.

## 🛠️ Outils & Sources utilisés

* **Agrégateurs :** Feedly.
* **Sources Institutionnelles :** ANSSI (CERT-FR), CISA, NCSC.
* **Bulletins Éditeurs :** FortiGuard Labs, Progress Security Center, Microsoft MSRC.
* **Intelligence Menaces :** The Hacker News, LeMagIT, BleepingComputer.

---

*⚠️ Disclaimer : Ce projet est une simulation éducative. L'entreprise Altergize est fictive, mais les vulnérabilités et les contextes réglementaires cités s'appuient sur des données réalistes ou des scénarios d'actualité simulés.*

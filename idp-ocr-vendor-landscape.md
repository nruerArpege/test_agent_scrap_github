# Paysage des Solutions IDP + OCR — Rapport de Veille Vendeurs

> **Objectif :** Identifier les entreprises proposant des solutions d'Intelligent Document Processing (IDP) basées principalement sur des technologies OCR, avec ou sans capacités de détection de fraude documentaire.
> **Périmètre :** Documents d'identité, factures, contrats, documents bancaires, assurance, réglementaires.
> **Date :** Avril 2026

---

## Table des matières

1. [Introduction](#introduction)
2. [Entreprises françaises](#entreprises-françaises)
   - [Finovox](#1-finovox)
   - [Luminess (IDP by Lumia)](#2-luminess-idp-by-lumia)
   - [Mindee](#3-mindee)
   - [Docaposte](#4-docaposte)
   - [Tessi](#5-tessi)
   - [Yooz](#6-yooz)
   - [Esker](#7-esker)
3. [Entreprises européennes (hors France)](#entreprises-européennes-hors-france)
   - [ABBYY](#8-abbyy)
   - [IDnow](#9-idnow)
   - [Klippa / Doxis AI.dp](#10-klippa--doxis-aidp)
   - [Rossum](#11-rossum)
   - [Veriff](#12-veriff)
   - [Onfido (Entrust)](#13-onfido-entrust)
   - [Sumsub](#14-sumsub)
   - [Tungsten Automation (ex-Kofax)](#15-tungsten-automation-ex-kofax)
4. [Vendeurs internationaux sélectionnés](#vendeurs-internationaux-sélectionnés)
   - [Jumio](#16-jumio)
   - [OpenText](#17-opentext)
5. [Tableau comparatif](#tableau-comparatif)
6. [Synthèse et recommandations](#synthèse-et-recommandations)

---

## Introduction

L'IDP (Intelligent Document Processing) désigne une catégorie de solutions qui vont au-delà du simple OCR traditionnel, en combinant :

- **OCR** (reconnaissance optique de caractères) pour extraire le texte des documents numérisés ou natifs
- **Classification automatique** des documents (factures, pièces d'identité, contrats…)
- **Extraction et validation** des données structurées et non structurées
- **Contrôles et règles métier** pour vérifier la cohérence des données extraites
- **(Optionnel) Détection de fraude documentaire** : falsification, altération, incohérences

Ce rapport couvre les solutions commerciales prêtes pour la production (B2B SaaS, API, plateformes), avec une forte priorité aux acteurs français, puis européens.

---

## Entreprises françaises

### 1. Finovox

| Attribut | Détail |
|---|---|
| **Site web** | [finovox.com](https://www.finovox.com/en) |
| **Pays** | 🇫🇷 France (Paris + Luxembourg) |
| **Fondée** | 2019 |

**Description de la solution IDP + OCR**

Finovox est une startup française spécialisée dans la vérification et l'anti-fraude documentaire. La plateforme automatise l'ensemble du cycle de vie de la vérification documentaire : collecte, classification, extraction OCR, validation et analyse forensique avancée. Elle prend en charge tous types de documents (pièces d'identité, factures, justificatifs, certificats) dans toutes les langues et alphabets. L'analyse d'un document est réalisée en moins de 30 secondes. Finovox propose à la fois une API pour l'intégration dans des workflows existants et une interface SaaS pour les investigations manuelles.

**Capacités de détection de fraude**

- Détection d'altérations visuelles et de falsifications par IA et machine learning
- Analyse des empreintes numériques et cohérence du contenu
- Détection des fraudes générées par l'IA générative (deepfakes documentaires)
- Rapports d'évidence avec preuves visuelles pour les équipes d'investigation
- En 2023 : analyse de plus de 1,2 million de documents ; objectif 5 millions en 2024

**Certifications et conformité**

- RGPD (données hébergées en Europe)
- Conformité KYC/KYB pour les services financiers
- Certifications spécifiques non publiquement listées — à demander sur devis

**Tarification**

- Modèle sur devis (enterprise sales) — pas de tarif public affiché
- Intégration API et accès SaaS plateforme d'investigation

**Clients et segments**

- HP (lutte contre la fraude aux garanties et aux factures)
- Bouygues Telecom, Orange Bank, Groupe IMA, PwC
- Secteurs : banque, assurance, télécoms, immobilier, secteur public

**Financement**

- Plus de 6 M€ levés au total, dont 4 M€ en 2024 (expansion internationale)
- ~20 employés ; expansion vers l'Italie, l'Espagne, le Royaume-Uni, le Québec, les USA, Singapour

---

### 2. Luminess (IDP by Lumia)

| Attribut | Détail |
|---|---|
| **Site web** | [luminess.eu](https://www.luminess.eu/en/solution-dintelligent-document-processing) |
| **Pays** | 🇫🇷 France |

**Description de la solution IDP + OCR**

Luminess propose une plateforme SaaS souveraine baptisée « IDP by Lumia » qui automatise le cycle de traitement documentaire de bout en bout. La solution couvre la capture, la classification, l'extraction des données, la validation, la détection de fraude, l'intégration e-signature et la conformité. Elle repose sur une combinaison d'OCR, NLP et modèles de langage de grande taille (LLM). Luminess cible les secteurs de la finance, de l'assurance et des télécoms, avec des workflows pré-packagés (KYC, onboarding, conformité) et des workflows personnalisables.

**Capacités de détection de fraude**

- Module de détection de fraude documentaire intégré
- Contrôles de cohérence, anomalie scoring
- Intégration avec les processus KYC/AML

**Certifications et conformité**

- **SecNumCloud** (certification souveraine ANSSI) — plateforme hébergée en France
- RGPD
- ISO 27001 (à vérifier selon les versions de déploiement)

**Tarification**

- Modèle SaaS sur abonnement, tarif sur devis selon volume et cas d'usage
- Déploiements pre-packagés et personnalisés disponibles

**Clients et segments**

- Finance, assurance, télécoms
- Cas d'usage prioritaires : KYC, onboarding, gestion de contrats

---

### 3. Mindee

| Attribut | Détail |
|---|---|
| **Site web** | [mindee.com](https://www.mindee.com) |
| **Pays** | 🇫🇷 France (Paris) |
| **Fondée** | 2018 |

**Description de la solution IDP + OCR**

Mindee est une startup parisienne qui propose des APIs OCR et IDP orientées développeurs (« developer-first »). La plateforme se distingue par son approche « training-free » : pas besoin d'annotation manuelle ni de ré-entraînement, grâce à une combinaison de deep learning, computer vision et LLM. Mindee propose plus de 20 endpoints documentaires pré-entraînés (factures, reçus, cartes d'identité, fiches de paie, relevés financiers, etc.) et un système d'extraction sur mesure via son offre docTI (Document Tailored Intelligence). Le traitement est en temps réel (environ 1 seconde par document).

**Capacités de détection de fraude**

- Pas de module de détection de fraude dédié nativement
- La plateforme peut être combinée avec des outils tiers de vérification d'authenticité
- Scoring de confiance sur les données extraites (aide à l'identification d'anomalies)

**Certifications et conformité**

- RGPD (données hébergées en Europe)
- Certifications SOC 2 / ISO 27001 non publiquement confirmées — à vérifier auprès du vendeur

**Tarification**

| Plan | Prix mensuel | Volume inclus | Prix à l'unité supplémentaire |
|---|---|---|---|
| Starter | ~44 €/mois | 500 pages | ~0,05 €/page |
| Pro | ~179 €/mois | 2 500 pages | ~0,04 €/page |
| Business | ~584 €/mois | 10 000 pages | ~0,035 €/page |
| Enterprise | Sur devis | >120 000 pages/an | Remises volume |

- Essai gratuit disponible (jusqu'à 250 pages/mois)

**Clients et segments**

- Services financiers, assurance, santé, logistique, construction, administration
- Profil client : équipes techniques, éditeurs SaaS, intégrateurs

**Financement**

- ~9–14 M$ levés (Alven Capital, Serena)
- 51–101 employés

---

### 4. Docaposte

| Attribut | Détail |
|---|---|
| **Site web** | [docaposte.com](https://www.docaposte.com/en/solutions/electronic-document-management) |
| **Pays** | 🇫🇷 France (filiale du Groupe La Poste) |

**Description de la solution IDP + OCR**

Docaposte est un acteur majeur de la confiance numérique et de la dématérialisation documentaire en France. Ses solutions intègrent l'OCR avancé avec l'IA pour la capture automatique, l'indexation et le traitement de documents papier et numériques (e-mails, PDF, images). La plateforme inclut la gestion électronique de documents (GED), la reconnaissance automatique de documents (RAD/OCR), l'archivage électronique probant, l'e-signature et la gestion de workflows de validation. Les données sont hébergées dans des datacenters français pour garantir la souveraineté.

**Capacités de détection de fraude**

- Contrôles de cohérence documentaire
- Vérification eIDAS (conformité signature électronique)
- Intégration possible avec des modules de détection de fraude tiers

**Certifications et conformité**

- **eIDAS** (prestataire de services de confiance qualifié)
- RGPD (hébergement France souverain)
- **HDS** (Hébergement de Données de Santé) pour les cas d'usage santé
- ISO 27001 (à confirmer selon le périmètre)

**Tarification**

- Modèle enterprise sur devis (tarification projet ou abonnement selon volume)
- Pas de tarif public affiché

**Clients et segments**

- Secteur public, banque, assurance, santé, télécoms
- Grands comptes et collectivités territoriales

---

### 5. Tessi

| Attribut | Détail |
|---|---|
| **Site web** | [tessi.fr](https://www.tessi.fr) |
| **Pays** | 🇫🇷 France |

**Description de la solution IDP + OCR**

Tessi est spécialisé dans l'externalisation de processus métier (BPO) et la numérisation documentaire à grande échelle. Sa plateforme IDP/OCR s'appuie sur des moteurs d'IA (dont un partenariat avec Smart Engines) pour traiter des millions de documents par an : pièces d'identité, formulaires, factures, courriers, documents manuscrits. Tessi couvre les documents structurés et non structurés, avec une forte capacité de traitement en masse.

**Capacités de détection de fraude**

- Vérification de l'authenticité des pièces d'identité
- Contrôles croisés et validation des données extraites
- Services de vérification documentaire pour KYC

**Certifications et conformité**

- RGPD
- Conformité réglementaire française et européenne
- Engagements de sécurité et de confidentialité documentés

**Tarification**

- Modèle sur devis (BPO + licence plateforme selon volume traité)

**Clients et segments**

- Secteur public, banque, assurance, mutuelles, grande distribution
- Traitement en masse (millions de documents/an)

---

### 6. Yooz

| Attribut | Détail |
|---|---|
| **Site web** | [getyooz.com](https://www.getyooz.com) |
| **Pays** | 🇫🇷 France |

**Description de la solution IDP + OCR**

Yooz est l'un des leaders français de l'automatisation Purchase-to-Pay (P2P), avec une suite IDP cloud pour le traitement des factures fournisseurs, bons de commande et notes de frais. La plateforme combine IA, machine learning et OCR avancé pour une capture « No Touch » depuis tous les canaux (e-mail, mobile, scanner, drag & drop). Yooz intègre plus de 250 ERP et systèmes comptables (SAP, Oracle, Sage, Cegid…). Le système s'auto-apprend pour améliorer la ventilation analytique.

**Capacités de détection de fraude**

- Détection de doublons de factures
- Validation des références bancaires et cohérence des données
- Rapprochement automatique avec les bons de commande (contrôle tri-directionnel)
- Module d'anomaly detection sur les données extraites

**Certifications et conformité**

- **ISO 27001** (sécurité de l'information)
- **SOC 1 Type 2**
- **RGPD** (données hébergées sur Microsoft Azure, datacenters européens)
- **PDP certifiée** : Plateforme de Dématérialisation Partenaire (réforme facturation électronique France, Factur-X, UBL, CII)

**Tarification**

- À partir de ~99 €/mois (selon volume de factures et modules)
- Essai gratuit 15 jours
- Utilisateurs illimités inclus dans l'abonnement
- Tarification entreprise sur devis pour volumes importants

**Clients et segments**

- Plus de 7 000 clients dans 50+ pays
- Banque, assurance, automobile, construction, hôtellerie, industrie, associations
- PME et grands comptes

---

### 7. Esker

| Attribut | Détail |
|---|---|
| **Site web** | [esker.com](https://www.esker.com) |
| **Pays** | 🇫🇷 France (Lyon) |

**Description de la solution IDP + OCR**

Esker est un acteur international de l'automatisation, avec des racines françaises fortes, spécialisé dans les processus Source-to-Pay et Order-to-Cash. Sa plateforme applique la capture documentaire AI-driven (OCR + IA), la gestion des factures et commandes clients, l'automatisation des workflows et la validation des données. Esker prend en charge les factures, commandes clients, réclamations et processus de paiement, avec une forte intégration ERP/CRM. La solution permet un traitement touchless de bout en bout.

**Capacités de détection de fraude**

- Contrôles de cohérence et validation des données fournisseurs
- Rapprochement automatisé (commande/réception/facture)
- Monitoring des anomalies dans les flux financiers

**Certifications et conformité**

- **ISO 27001**
- **SOC 1 & SOC 2**
- **RGPD**
- Conformité e-facturation France (Chorus Pro, Factur-X)

**Tarification**

- Modèle sur devis (enterprise sales, tarification selon volume et modules)

**Clients et segments**

- Grandes entreprises, ETI, secteur public
- Finance, logistique, industrie, retail

---

## Entreprises européennes (hors France)

### 8. ABBYY

| Attribut | Détail |
|---|---|
| **Site web** | [abbyy.com](https://www.abbyy.com) |
| **Pays** | 🇩🇪 Allemagne (siège européen) / International |

**Description de la solution IDP + OCR**

ABBYY est l'un des leaders mondiaux de l'IDP et de l'OCR, avec plus de 30 ans d'expertise. Sa plateforme phare **ABBYY Vantage** est une solution IDP cloud-native basée sur des microservices conteneurisés, avec des « Skills » documentaires pré-entraînés et personnalisables. Elle supporte 200+ langues, excelle sur les documents petits caractères et denses, et couvre tous types de documents (factures, contrats, KYC, santé…). Les SDKs sont disponibles en Python, C#, Java, TypeScript. La solution peut être déployée en SaaS, on-premise ou hybride.

**Capacités de détection de fraude**

- Règles métier et anomaly detection sur les données extraites
- Intégration avec des workflows de validation avancée
- Capacités de cross-validation avec sources externes

**Certifications et conformité**

- **ISO/IEC 27001:2013** (recertifié mars 2023, valide jusqu'en mars 2026)
- **ISO 9001:2015** (qualité)
- **SOC 2 Type 2** (ABBYY Vantage, FlexiCapture Cloud, Timeline, OCR SDK)
- RGPD, CCPA

**Tarification**

- Sur devis (enterprise sales) — pas de tarif public
- Dépend du produit (Vantage, FlexiCapture, FineReader), du déploiement et du volume

**Clients et segments**

- Plus de 10 000 clients mondiaux : McDonald's, Siemens, PepsiCo, Volkswagen UK, Deloitte, Ricoh
- Finance, santé, légal, administration, audit

---

### 9. IDnow

| Attribut | Détail |
|---|---|
| **Site web** | [idnow.io](https://www.idnow.io) |
| **Pays** | 🇩🇪 Allemagne (Munich) |

**Description de la solution IDP + OCR**

IDnow propose une plateforme d'Identity Verification (IDV) et de document processing couvrant plus de 3 700 types de documents issus de 215+ autorités émettrices. La solution combine vérification automatique (OCR + biométrie) et revue humaine vidéo, avec authentification NFC et détection de vie (liveness). IDnow est particulièrement fort sur la conformité réglementaire européenne (eIDAS 2.0, AMLR, PSD3) et les pistes d'audit.

**Capacités de détection de fraude**

- Prévention de fraude en temps réel par IA
- Technologie anti-deepfake
- Vérification d'authenticité documentaire multi-couches
- Conformité AMLR et trails d'audit pour les services financiers

**Certifications et conformité**

- **eIDAS 2.0** (prestataire de services de confiance)
- RGPD
- Conformité AMLR, PSD3
- ISO 27001 (à vérifier)

**Tarification**

- Sur devis (enterprise sales)

**Clients et segments**

- Services financiers, fintech, assurance, secteur public européen
- Fort ancrage réglementaire UE

---

### 10. Klippa / Doxis AI.dp

| Attribut | Détail |
|---|---|
| **Site web** | [klippa.com](https://www.klippa.com) / [ser-group.com](https://www.ser-group.com) |
| **Pays** | 🇳🇱 Pays-Bas (Klippa, acquis par SER Group 🇩🇪 Allemagne) |

**Description de la solution IDP + OCR**

Klippa DocHorizon (rebaptisé **Doxis AI.dp** après acquisition par SER Group) est une plateforme IDP reconnue pour sa précision d'extraction (jusqu'à 99%) et ses capacités avancées de détection de fraude documentaire. La solution couvre la capture, classification, extraction et vérification de tous types de documents. Elle est particulièrement adaptée aux secteurs nécessitant une vérification stricte d'authenticité (finance, assurance, KYC/AML).

**Capacités de détection de fraude**

- Forensics documentaire multi-couches par deep learning
- Analyse EXIF et métadonnées
- Détection d'anomalies de police, de dates et de champs altérés
- Cross-validation avec sources externes
- Spécialement conçu pour la détection de fraude à l'assurance (sinistres)

**Certifications et conformité**

- **ISO 9001** et **ISO 27001**
- RGPD
- Certification Peppol (échange de factures électroniques)
- Conformité avec les systèmes ECM européens

**Tarification**

- Sur devis (enterprise sales) après acquisition par SER Group

**Clients et segments**

- Finance, assurance, KYC/AML, secteur public
- Clientèle principalement européenne

---

### 11. Rossum

| Attribut | Détail |
|---|---|
| **Site web** | [rossum.ai](https://rossum.ai) |
| **Pays** | 🇨🇿 République tchèque (Prague) |

**Description de la solution IDP + OCR**

Rossum est une plateforme IDP spécialisée dans l'automatisation des workflows transactionnels (factures, bons de commande, documents financiers). Elle repose sur des LLM documentaires supportant 276 langues, avec une extraction zéro hallucination, un apprentissage continu et une forte intégration ERP/SAP/Oracle. La solution se positionne sur les processus à fort volume avec une précision élevée et des pistes d'audit complètes.

**Capacités de détection de fraude**

- Validation croisée des données avec les ERP, maîtres données et APIs tierces
- Moteur de règles métier pour bloquer les transactions suspectes
- Anomaly detection transactionnel (pas de forensics image nativement)
- Archivage documentaire avec logs complets

**Certifications et conformité**

- RGPD
- Pistes d'audit complètes et archivage documentaire
- Certifications spécifiques à demander auprès du vendeur

**Tarification**

- Sur devis (enterprise sales)

**Clients et segments**

- Grandes entreprises, finance, logistique, retail, services partagés
- Fort en AP/AR automation

---

### 12. Veriff

| Attribut | Détail |
|---|---|
| **Site web** | [veriff.com](https://www.veriff.com) |
| **Pays** | 🇪🇪 Estonie (Tallinn) |

**Description de la solution IDP + OCR**

Veriff propose une plateforme de vérification d'identité et de documents couvrant plus de 13 500 types de documents issus de 230+ pays. L'OCR automatisé, la biométrie faciale et la détection de vie permettent une décision de vérification en environ 6 secondes. La solution est reconnue pour sa facilité d'intégration (API/SDK) et sa haute couverture mondiale.

**Capacités de détection de fraude**

- Risk Labels, FaceBlock et CrossLinks (signaux de fraude croisés)
- Équipe interne de monitoring des fraudes
- Faible taux de fausse acceptation
- Détection de tentatives de spoofing et de deepfakes

**Certifications et conformité**

- RGPD
- ISO 27001
- Conformité KYC/AML

**Tarification**

- Tarification transparente disponible sur leur site (modèle par vérification)
- Plans enterprise sur devis

**Clients et segments**

- Fintech, crypto, gaming, transport, marketplace
- Clients européens et mondiaux nécessitant une vérification à fort taux de conversion

---

### 13. Onfido (Entrust)

| Attribut | Détail |
|---|---|
| **Site web** | [entrust.com/products/identity-verification](https://www.entrust.com/products/identity-verification/) |
| **Pays** | 🇬🇧 Royaume-Uni (acquis par Entrust 🇺🇸) |

**Description de la solution IDP + OCR**

Onfido (désormais intégré à Entrust) est une référence mondiale de la vérification documentaire, couvrant 2 500+ types de documents dans 195 pays. La solution combine IA et revue humaine pour la vérification des pièces d'identité, avec des SDKs offrant un retour en temps réel pour améliorer la qualité des soumissions.

**Capacités de détection de fraude**

- Détection de documents falsifiés, contrefaits, volés, fantômes et de camouflage
- Catch rate de 98,7% des tentatives de fraude documentaire
- Biométrie faciale et liveness detection

**Certifications et conformité**

- RGPD
- Conformité KYC/AML
- ISO 27001

**Tarification**

- Sur devis (enterprise sales)

**Clients et segments**

- Banques et fintechs UK/EU
- Onboarding réglementé, conformité KYC

---

### 14. Sumsub

| Attribut | Détail |
|---|---|
| **Site web** | [sumsub.com](https://sumsub.com) |
| **Pays** | 🇬🇧 Royaume-Uni / Chypre |

**Description de la solution IDP + OCR**

Sumsub propose une suite complète de vérification (KYC, KYB, AML, monitoring transactionnel, prévention de fraude) couvrant plus de 6 500 types de documents dans 220+ pays. L'onboarding prend généralement moins de 50 secondes. La plateforme est reconnue pour ses taux de conversion élevés (jusqu'à 97%+) et ses certifications européennes avancées.

**Capacités de détection de fraude**

- Détection de deepfakes et de spoofing
- AML monitoring et surveillance transactionnelle
- Matching biométrique et liveness detection

**Certifications et conformité**

- **ETSI EN 319 401, EN 319 411-1, EN 319 411-2, TS 119 461** (certifications eIDAS pour prestataires de confiance)
- Qualified Electronic Signature (QES) compliant
- RGPD
- Conforme AMLR/PSD3

**Tarification**

| Plan | Prix | Volume |
|---|---|---|
| Basic | 1,35 $/vérification (min. 149 $/mois) | Standard |
| Compliance | 1,85 $/vérification (min. 299 $/mois) | + AML, justificatif domicile |
| Enterprise | Sur devis | Volume élevé |

- Essai gratuit 14 jours (50 vérifications)

**Clients et segments**

- Fintech, crypto, gaming, transport
- Forte adoption en Europe pour les obligations eIDAS/AML

---

### 15. Tungsten Automation (ex-Kofax)

| Attribut | Détail |
|---|---|
| **Site web** | [tungstenautomation.com](https://www.tungstenautomation.com) |
| **Pays** | 🇬🇧 Royaume-Uni / International (rebaptisé 2024) |

**Description de la solution IDP + OCR**

Tungsten Automation (anciennement Kofax) est un leader reconnu de l'automatisation documentaire et de l'IDP enterprise. Sa plateforme **TotalAgility** combine OCR (moteurs OmniPage, Kofax Clarity, FormXtra), IA/ML, NLP et orchestration de processus pour traiter à grande échelle des documents structurés, semi-structurés et non structurés (factures, identités, contrats, formulaires, e-mails). Déploiement on-premise, cloud privé ou Azure.

**Capacités de détection de fraude**

- Validation et règles métier sur les données extraites
- Intégration avec des moteurs de détection de fraude tiers
- Conformité et audit documentaire

**Certifications et conformité**

- RGPD
- Conformité e-facturation européenne (eIDAS)
- ISO 27001 (à vérifier selon déploiement)

**Tarification**

- Sur devis (enterprise sales)

**Clients et segments**

- Banque, assurance, gouvernement, grandes entreprises
- Fort en Europe et Amérique du Nord

---

## Vendeurs internationaux sélectionnés

### 16. Jumio

| Attribut | Détail |
|---|---|
| **Site web** | [jumio.com](https://www.jumio.com) |
| **Pays** | 🇺🇸 États-Unis |

**Description de la solution IDP + OCR**

Jumio est un leader mondial de la vérification d'identité et du document processing, couvrant 5 000+ types de documents dans 200+ pays. La solution combine OCR avancé, biométrie, liveness detection et IA pour une vérification automatisée ou avec revue humaine. Jumio est particulièrement adapté aux plateformes à fort volume nécessitant une conformité KYC/AML stricte.

**Capacités de détection de fraude**

- Détection de fraude documentaire par IA/ML
- Vérification biométrique et anti-spoofing
- Scoring de risque avancé

**Certifications et conformité**

- **PCI DSS Level 1**
- RGPD
- Conformité KYC/AML internationale

**Tarification**

- Pas de tarif public affiché
- Dépense médiane annuelle : ~55 850 $ (fourchette : 5 800 $ – 213 000 $/an selon volume)
- Contrats annuels minimaux typiquement à partir de 25 000 $

**Clients et segments**

- Fintech, crypto, sharing economy, banque
- Clients enterprise mondiaux

---

### 17. OpenText

| Attribut | Détail |
|---|---|
| **Site web** | [opentext.com](https://www.opentext.com) |
| **Pays** | 🇨🇦 Canada / International |

**Description de la solution IDP + OCR**

OpenText est un leader mondial de la gestion de contenu d'entreprise (ECM) et de l'IDP. **OpenText Content Cloud** offre une capture documentaire intelligente de bout en bout, classification, extraction, validation et automatisation des workflows. La solution s'intègre profondément avec SAP, Salesforce et les principaux ERP, et peut être déployée on-premise, en cloud privé ou sur hyperscaleurs (AWS, Azure, GCP) — garantissant la résidence des données en Europe pour la conformité RGPD.

**Capacités de détection de fraude**

- Détection d'anomalies par IA sur les flux documentaires
- Intégration avec des modules d'audit et de conformité
- Archivage probant

**Certifications et conformité**

- RGPD (résidence des données en Europe disponible)
- ISO 27001
- SOC 2

**Tarification**

- Sur devis (enterprise sales)

**Clients et segments**

- Très grandes entreprises, multinationales, secteur public
- Finance, santé, gouvernement, industrie

---

## Tableau comparatif

| # | Entreprise | Pays | OCR | Classification | Extraction | Validation | Fraude | ISO 27001 | SOC 2 | RGPD | SecNumCloud | Tarification | Segments principaux |
|---|---|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|---|---|
| 1 | **Finovox** | 🇫🇷 | ✅ | ✅ | ✅ | ✅ | ✅✅ | ❓ | ❓ | ✅ | ❌ | Sur devis | Banque, assurance, télécoms |
| 2 | **Luminess** | 🇫🇷 | ✅ | ✅ | ✅ | ✅ | ✅ | ❓ | ❓ | ✅ | ✅ | Sur devis | Finance, assurance, télécoms |
| 3 | **Mindee** | 🇫🇷 | ✅ | ✅ | ✅ | ⚠️ | ❌ | ❓ | ❓ | ✅ | ❌ | À partir de 44 €/mois | Fintech, SaaS, assurance |
| 4 | **Docaposte** | 🇫🇷 | ✅ | ✅ | ✅ | ✅ | ⚠️ | ❓ | ❓ | ✅ | ⚠️ | Sur devis | Secteur public, banque, santé |
| 5 | **Tessi** | 🇫🇷 | ✅ | ✅ | ✅ | ✅ | ⚠️ | ❓ | ❓ | ✅ | ❌ | Sur devis | Secteur public, banque, assurance |
| 6 | **Yooz** | 🇫🇷 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | À partir de 99 €/mois | PME, banque, assurance, industrie |
| 7 | **Esker** | 🇫🇷 | ✅ | ✅ | ✅ | ✅ | ⚠️ | ✅ | ✅ | ✅ | ❌ | Sur devis | Grandes entreprises, finance |
| 8 | **ABBYY** | 🇩🇪 | ✅✅ | ✅ | ✅ | ✅ | ⚠️ | ✅ | ✅ | ✅ | ❌ | Sur devis | Finance, santé, légal, industrie |
| 9 | **IDnow** | 🇩🇪 | ✅ | ✅ | ✅ | ✅ | ✅ | ❓ | ❓ | ✅ | ❌ | Sur devis | Finance, fintech, secteur public |
| 10 | **Klippa/Doxis** | 🇳🇱/🇩🇪 | ✅ | ✅ | ✅ | ✅ | ✅✅ | ✅ | ❓ | ✅ | ❌ | Sur devis | Finance, assurance, KYC |
| 11 | **Rossum** | 🇨🇿 | ✅ | ✅ | ✅ | ✅ | ⚠️ | ❓ | ❓ | ✅ | ❌ | Sur devis | Finance, logistique, retail |
| 12 | **Veriff** | 🇪🇪 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❓ | ✅ | ❌ | Par vérification | Fintech, crypto, gaming |
| 13 | **Onfido/Entrust** | 🇬🇧 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❓ | ✅ | ❌ | Sur devis | Banque, fintech |
| 14 | **Sumsub** | 🇬🇧 | ✅ | ✅ | ✅ | ✅ | ✅ | ❓ | ❓ | ✅ | ❌ | 1,35–1,85 $/vérif | Fintech, crypto, transport |
| 15 | **Tungsten Auto.** | 🇬🇧 | ✅✅ | ✅ | ✅ | ✅ | ⚠️ | ❓ | ❓ | ✅ | ❌ | Sur devis | Banque, assurance, gouvernement |
| 16 | **Jumio** | 🇺🇸 | ✅ | ✅ | ✅ | ✅ | ✅ | ❓ | ❓ | ✅ | ❌ | ~55 K$/an | Fintech, crypto, banque |
| 17 | **OpenText** | 🇨🇦 | ✅ | ✅ | ✅ | ✅ | ⚠️ | ✅ | ✅ | ✅ | ❌ | Sur devis | Très grandes entreprises |

**Légende :**
- ✅ = Fonctionnalité présente / Certification confirmée
- ✅✅ = Capacité particulièrement forte dans ce domaine
- ⚠️ = Capacité partielle ou via intégration tierce
- ❌ = Non disponible / Non applicable
- ❓ = Non confirmé publiquement — à vérifier auprès du vendeur

---

## Synthèse et recommandations

### Classement par maturité « all-in-one »

**Niveau 1 — Plateformes IDP complètes avec fraude intégrée**

Ces solutions couvrent l'intégralité du cycle : OCR → Classification → Extraction → Validation → Détection de fraude dans un seul produit cohérent :

1. 🇫🇷 **Finovox** — Spécialiste français de la fraude documentaire avec IDP complet. Solution idéale quand la fraude est la priorité absolue.
2. 🇫🇷 **Luminess** — Plateforme souveraine SecNumCloud, adaptée aux organisations nécessitant une certification de sécurité française.
3. 🇳🇱🇩🇪 **Klippa / Doxis AI.dp** — Meilleure solution européenne pour la forensics documentaire avancée.
4. 🇩🇪 **IDnow** — Référence pour la conformité réglementaire européenne (eIDAS 2.0, AML).

**Niveau 2 — Plateformes IDP robustes (fraude partielle ou via intégration)**

5. 🇫🇷 **Yooz** — Meilleur rapport qualité/prix/certification pour les PME françaises (factures, AP/P2P).
6. 🇫🇷 **Esker** — Solide pour les grandes entreprises sur Order-to-Cash et Source-to-Pay.
7. 🇩🇪 **ABBYY** — Standard mondial de l'OCR, platforme IDP mature et certifiée.
8. 🇬🇧 **Onfido / Entrust** — Référence pour la vérification documentaire KYC.
9. 🇪🇪 **Veriff** — Forte performance et transparence tarifaire, idéal pour les fintechs.
10. 🇬🇧 **Sumsub** — Meilleure couverture ETSI/eIDAS avec tarification accessible.

**Niveau 3 — OCR/IDP spécialisé ou orienté développeurs**

11. 🇫🇷 **Mindee** — Idéal pour les équipes techniques cherchant une API OCR performante à intégrer.
12. 🇨🇿 **Rossum** — Fort sur la validation transactionnelle et l'intégration ERP.
13. 🇫🇷 **Docaposte** — Robuste pour le secteur public et la santé avec souveraineté française.
14. 🇫🇷 **Tessi** — BPO et traitement en masse, notamment pour le secteur public.

### Recommandations par cas d'usage

| Cas d'usage | Acteurs recommandés |
|---|---|
| Fraude documentaire prioritaire | Finovox 🇫🇷, Klippa/Doxis 🇳🇱🇩🇪, Onfido/Entrust 🇬🇧 |
| Souveraineté française impérative | Luminess 🇫🇷 (SecNumCloud), Docaposte 🇫🇷 |
| Facturation / AP automation | Yooz 🇫🇷, Esker 🇫🇷, Rossum 🇨🇿 |
| KYC/AML réglementaire EU | IDnow 🇩🇪, Sumsub 🇬🇧, Veriff 🇪🇪 |
| API OCR pour développeurs | Mindee 🇫🇷, ABBYY Vantage 🇩🇪 |
| IDP enterprise grande échelle | ABBYY 🇩🇪, Tungsten Automation 🇬🇧, OpenText 🇨🇦 |
| Secteur public / santé France | Docaposte 🇫🇷 (HDS), Tessi 🇫🇷 |

### Points de vigilance

- **Certifications** : Beaucoup de vendeurs ne publient pas leurs certifications en ligne. Il est indispensable de demander les rapports SOC 2, ISO 27001 et HDS/SecNumCloud directement sous NDA lors de la qualification.
- **Tarification** : La majorité des solutions B2B sont sur devis. Seuls Mindee, Yooz (entrée de gamme) et Sumsub ont des grilles publiques.
- **Souveraineté** : Pour les organisations soumises aux exigences de l'ANSSI (SecNumCloud), seule **Luminess** affiche cette certification nativement. Docaposte offre une hébergement souverain avec d'autres qualifications.
- **Fraude documentaire vs. fraude identitaire** : Finovox et Klippa se distinguent sur la fraude documentaire (forensics, altération) ; Veriff, IDnow, Onfido et Sumsub sont davantage orientés fraude identitaire (biométrie, liveness).

---

*Rapport généré en avril 2026. Les informations sont susceptibles d'évoluer ; il est recommandé de vérifier directement auprès de chaque vendeur pour les certifications, tarifications et offres produit à jour.*

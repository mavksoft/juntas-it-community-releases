<p align="center">
  <img src="https://it-community.online/assets/logo.png" alt="IT-Community" width="96">
</p>

<h1 align="center">Juntas — IT-Community</h1>

<p align="center">L'app d'assemblées de copropriété de l'écosystème IT-Community.<br>Convocations, documents et accès au portail de votre communauté — sur Android, iOS, Windows et macOS.</p>

<p align="center">
  <a href="https://it-community.online"><img src="https://img.shields.io/badge/website-it--community.online-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/juntas-it-community-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/juntas-it-community-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-Android%20%C2%B7%20iOS%20%C2%B7%20Windows%20%C2%B7%20macOS-black" alt="platforms">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/juntas-it-community-releases/"><img src="https://img.shields.io/badge/docs-mavksoft.github.io%2Fjuntas-it-community-releases-blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <strong>🇫🇷 Français</strong> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Ce dépôt publie uniquement les releases officielles** — le code source est privé. Téléchargements signés, sommes de contrôle et flux de mise à jour automatique.

## Téléchargement

| | |
|---|---|
| 📥 **macOS** | [Juntas-<version>.dmg](https://github.com/mavksoft/juntas-it-community-releases/releases/latest) dans chaque release |
| 📱 **Mobile** | Android et iOS — depuis les stores ou via [it-community.online](https://it-community.online) |
| 🪟 **Windows** | Installateur disponible dans chaque release |
| 🌍 **Site officiel** | [it-community.online](https://it-community.online) |

## Qu'est-ce que c'est

Juntas est l'application d'assemblées de l'écosystème IT-Community : elle se connecte au portail de votre copropriété pour recevoir les convocations, consulter les documents de chaque assemblée et suivre la vie de votre communauté depuis n'importe quel appareil. Ce dépôt distribue les binaires publics et les flux d'auto-mise à jour.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Fonctionnalités

- **Connexion au portail** — l'app se lie au portail IT-Community de votre copropriété via le répertoire `portals.json`.
- **Multi-plateforme** — builds pour Android, iOS, Windows et macOS.
- **Auto-mise à jour** — `version.json` et `appcast.xml` alimentent l'updater intégré.
- **Documents des assemblées** — convocations, procès-verbaux et annexes du portail, sur mobile et bureau.

## Mode d'emploi

1. Téléchargez le build de votre plateforme depuis la dernière release (ou installez l'app mobile depuis votre store).
2. Ouvrez l'app et trouvez votre communauté dans le répertoire des portails.
3. Connectez-vous avec les identifiants fournis par votre administrateur de biens.
4. Consultez convocations, PV et documents de chaque assemblée depuis l'app.

## Configuration requise

Android, iOS, Windows 10+ ou macOS récent · Requiert un portail IT-Community actif pour votre copropriété (géré par votre administrateur de biens).

## Contenu de ce dépôt

- `Juntas-<version>.dmg` — installateur macOS signé
- `Juntas-<version>.zip` — build empaqueté / archive d'auto-update
- `version.json` — flux de version pour l'updater de l'app
- `appcast.xml` — flux Sparkle pour macOS
- `portals.json` — répertoire des portails IT-Community utilisé par l'app
- Le code source vit dans le repo privé `mavksoft/juntas-it-community`.

[Dernière version](https://github.com/mavksoft/juntas-it-community-releases/releases/latest)

## Questions fréquentes

**Puis-je utiliser l'app sans portail pour ma copropriété ?**  
L'app nécessite un portail IT-Community actif — configuré par l'administrateur de biens de votre copropriété.

**Où est le code source ?**  
Logiciel privé : ce dépôt ne publie que les binaires et les flux de mise à jour.

## Assistance

- Site : [it-community.online](https://it-community.online)
- E-mail : [hola@it-community.online](mailto:hola@it-community.online)

---
<p align="center"><sub>Juntas — IT-Community · © MavkSoft / IT-Systems</sub></p>

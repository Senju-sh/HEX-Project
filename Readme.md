# 💠 HEX-PROJECT — Selfbot Discord Privé

> ⚠️ Ce dépôt est fourni à titre **informatif et éducatif uniquement**.
-  J'hésite a poster des trucs + personnels 🤡

## 📦 À propos

HEX-PROJECT est un selfbot Discord avancé, conçu pour automatiser des tâches, personnaliser l’expérience utilisateur, et offrir une panoplie de commandes modulaires. Il repose sur `discord.js-selfbot-v13`, une version modifiée de Discord.js permettant l’usage de comptes utilisateurs.

- 🔧 Langage : JavaScript (Node.js)
- 🧠 Architecture : modulaire, orientée commandes & événements
- 📁 Organisation : séparation claire entre gestion, commandes, événements, et utilitaires

## 🗂️ Structure du projet

```
src/
├── Manager/
│   └── commands/ → Gestion Buyer, Premium, Selfbot, Users
├── events/
│   └── Client/ → buyers.json, codes.json, demandes.json
├── Selfbot/
│   └── commands/ → account, antibot, backups, friends, fun, help, logs, love, moderation, ...
├── structures/
utils/
├── backups/
└── db/ → example.json

Fichiers racine : .gitignore, codes.json, config.json, index.js, package.json
```

## 🚀 Installation

### 1. Cloner le dépôt

```bash
git clone https://github.com/Senju-sh/HEX-Project
cd HEX-Project
```

### 2. Installer les dépendances

```bash
npm install
```

### 3. Configurer le selfbot

Modifiez le fichier `config.json` avec vos informations :

```json
{
  "manager": "BOT TOKEN",
  "premium": false,
  "logChannel": "",
  "guild_id": "",
  "staff_role": "",
  "whitelist_role": "",
  "owners": ["id1","id2"],
  "tokens": [
    "token1",
    "token2",
  ]
}
```

## 🧩 Fonctionnalités

### 🔐 Gestion & accès

- Buyers / Premium / Owners
- Attribution automatique des rôles
- Système de codes et demandes

### 🎮 Commandes Selfbot

- `account` : infos du compte
- `backups` : sauvegarde/restauration de serveurs via `discord-backup`
- `friends`, `love`, `fun` : interactions sociales
- `moderation` : kick, ban, purge
- `spotify`, `status`, `voice` : personnalisation d’activité
- `tools`, `utils`, `logs` : outils divers
- `nsfw`, `raid`, `antibot` : modules sensibles (⚠️ à utiliser avec précaution)

### 📅 Automatisation

- `node-cron` pour planifier des tâches
- `speakeasy` pour la gestion de 2FA ou OTP

## 📚 Dépendances clés

| Package | Usage |
|--------|-------|
| `discord.js-selfbot-v13` | Base du selfbot |
| `discord.js` | Compatibilité avec les structures modernes |
| `discord-backup` | Sauvegarde/restauration de serveurs |
| `canvas` | Génération d’images |
| `archiver` | Compression de fichiers |
| `node-cron` | Tâches planifiées |
| `speakeasy` | OTP / 2FA |

## 🧪 Lancer le bot

```bash
npm run test
```

Ou simplement :

```bash
node index.js
```

## 🐞 Bugs & contributions

- [Signaler un bug](https://github.com/Senju-sh/HEX-Project/issues)
- [Page d’accueil du projet](https://github.com/Senju-sh/HEX-Project#readme)

## 📜 Licence

Ce projet est sous licence **ISC**. Aucune garantie n’est fournie. Usage à vos risques et périls.

---

## ❗ Disclaimer

L’usage de selfbots est **interdit par Discord**. Ce projet est fourni à des fins **éducatives uniquement**. L’auteur ne pourra être tenu responsable de tout usage abusif.

---
## 📝 Licence

Ce projet est sous licence **MIT**. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

## 👨‍💻 Créateur

**HEX** a été créé avec ❤️ par **Senju**

- **GitHub** : [@Senju](https://github.com/senju-sh)
- **Version actuelle** : 1.0.0

---

<div align="center">

**⭐ N'oubliez pas de mettre une étoile si ce projet vous plaît ! ⭐**

*Développé avec passion pour la communauté Discord*

</div>

# 🌐 Horizonbot (version Replit)

Bot Discord complet avec modération, logs, utilitaires. Ce projet est adapté pour **Replit**.

---

## 🧰 Fonctionnalités

- 🔨 `!ban`, `!kick`, etc.
- 📋 Logs (message supprimé, édité, changement de rôle)
- 📦 Organisation en cogs (modulaire)

---

## 🚀 Hébergement sur Replit

### 1. Importer le projet

- Va sur [https://replit.com](https://replit.com)
- Crée un nouveau Replit > Import depuis un ZIP ou GitHub
- Dépose le contenu de `Horizonbot_Final.zip` (décompressé)

### 2. Ajouter le fichier `.env`

Clique sur le bouton **Secrets** (icône verrou à gauche) et ajoute :

| Nom   | Valeur           |
|-------|------------------|
| TOKEN | ton_token_discord |

---

### 3. Lancer le bot

Clique sur **Run** dans Replit.  
Le bot devrait afficher :
```
Logged in as Horizonbot#1234!
```

---

### 📁 Structure

```
Horizonbot/
├── bot/
│   ├── cogs/
│   │   ├── moderation.py
│   │   ├── utility.py
│   │   └── logs.py
│   └── main.py
├── .env (via Secrets)
├── requirements.txt
├── .replit
├── replit.nix
└── README.md
```

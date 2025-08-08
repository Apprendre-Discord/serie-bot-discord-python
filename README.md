# 🤖 Créer son premier bot Discord en Python (Épisode 1)

Ce projet correspond à la première vidéo de la série **"Créer un bot Discord en Python"**.  
Dans cet épisode, on configure l'environnement, on crée un bot, et on lui fait répondre à une commande simple `!ping`.

---

## 🚀 Étapes pour lancer le bot

### 1️⃣ Installer Python et les dépendances

- Téléchargez et installez **[Python 3.10+](https://www.python.org/downloads/)**  
   _(Cochez bien l'option "Add Python to PATH" lors de l'installation)_
- Ouvrez un terminal dans le dossier du projet
- Créez et activez un environnement virtuel :

```bash
python -m venv venv
venv\Scripts\activate   # Windows
# ou
source venv/bin/activate   # Mac/Linux
```

### 2️⃣ Créer un bot sur le Discord Developer Portal

- Allez sur **[Discord Developer Portal](https://discord.com/developers/applications)**
- Créez une nouvelle application
- Ajoutez un bot à l'application
- Activez l'intent **Message Content**
- Copiez le token du bot
- Générez un lien d'invitation avec les permissions (Admin pour tester)
- Invitez le bot sur votre serveur

### 3️⃣ Configurer le fichier .env

- Créez un fichier `.env` à la racine du projet
- Ajoutez dedans :

```env
DISCORD_TOKEN=VotreTokenIci
```

> ⚠️ **Ne partagez jamais votre token**  
> Ajoutez `.env` dans votre `.gitignore` pour éviter de l'envoyer sur GitHub.

### 4️⃣ Lancer le bot

Dans le terminal, exécutez :

```bash
python main.py
```

Si tout fonctionne, le terminal affichera que le bot est connecté.

Testez dans Discord :

```
!ping
```

Le bot doit répondre :

```
Pong !
```

---

## 📂 Structure du projet

```
mon-bot-discord/
├── main.py
├── .env
├── requirements.txt
└── venv/ (environnement virtuel)
```

---

## 📜 Licence

Vous pouvez utiliser et modifier ce code librement pour vos projets personnels ou éducatifs.

---

## 🎥 Retrouvez le tutoriel complet en vidéo :

[Lien vers la vidéo YouTube](#)

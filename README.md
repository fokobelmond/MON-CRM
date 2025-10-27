# 🧩 Mini CRM — Gestionnaire de Contacts

## 🚀 Présentation
**Mini CRM** est une application web full-stack permettant de gérer vos contacts facilement et efficacement. Distribuée sous forme d’archive `.zip`, elle combine un **frontend React** et un **backend Flask**, offrant une expérience fluide, moderne et professionnelle.

## ✨ Fonctionnalités
- Ajouter, visualiser et supprimer des contacts  
- Validation automatique des emails et numéros français  
- Interface responsive : tableau sur desktop / cartes sur mobile  
- Design moderne avec animations douces  
- Séparation claire entre backend et frontend

## 🧰 Technologies utilisées
**Frontend** : React 18 + TypeScript, Mantine UI, Vite  
**Backend** : Flask (Python 3.8+), SQLite, Flask-SQLAlchemy, Flask-CORS

## 📦 Instructions d’installation et d’utilisation
### 1. Décompresser l’archive
Extraire le fichier **`mini-crm.zip`** dans un dossier de votre choix.

### 2. Lancer le backend
Ouvrir un terminal et naviguer dans le dossier backend :

```bash
cd backend
```

#### Windows
```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

#### Linux / macOS
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
```

➡️ Le backend sera accessible sur **http://localhost:5000**

### 3. Lancer le frontend
Ouvrir un nouveau terminal et naviguer dans le dossier frontend :

```bash
cd frontend
npm install
npm run dev
```

➡️ Le frontend sera accessible sur **http://localhost:5173**

### 4. Accéder à l’application
Ouvrir votre navigateur et aller sur :  
```
http://localhost:5173
```

L’application est prête à être utilisée !

## 📂 Structure du projet
```text
mini-crm/
├── backend/       # Serveur Flask et base de données
├── frontend/      # Application React
├── requirements.txt
├── package.json
├── README.md
└── LICENSE.txt
```

## ⚡ Utilisation
- Ajouter un contact via le formulaire  
- Visualiser la liste des contacts avec informations détaillées  
- Supprimer un contact si nécessaire  
- Les validations sont automatiques et les erreurs affichées en temps réel

## 🧠 Remarques
- Base SQLite locale, données persistantes  
- Interface responsive et compatible tous navigateurs modernes  
- Projet distribué sous forme compressée `.zip` pour simplifier l’installation

## 👤 Auteur
**Neil Belmond FOKO FEGUEM**  
GitHub : [@fokobelmond](https://github.com/fokobelmond)  
LinkedIn : [Neil Belmond FOKO FEGUEM](https://www.linkedin.com/in/neilbelmond/)

## 📄 Licence
MIT License — © 2025 Neil Belmond FOKO FEGUEM  
Voir `LICENSE.txt` pour plus de détails.

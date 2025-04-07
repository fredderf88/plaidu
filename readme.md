# Proxy Plaid pour Railway

Ce projet permet d'utiliser l'environnement `development` de Plaid depuis Google Sheets (via Apps Script) en passant par un proxy sécurisé hébergé sur Railway.

## 🚀 Déploiement

1. Crée un compte sur [https://railway.app](https://railway.app)
2. Crée un projet > "Deploy from GitHub" ou "Blank project"
3. Ajoute ces variables d'environnement :

   - `PLAID_CLIENT_ID`
   - `PLAID_SECRET`
   - `PLAID_ENV=development`

4. Railway te fournit une URL publique, ex :

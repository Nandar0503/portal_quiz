# Knowledge Hub BMKG 196 — Firebase Ready

## 1. Firebase project
Create a Firebase project and add a Web App. Copy its config into `public/js/firebase-config.js`.

## 2. Enable services
- Authentication: Email/Password (or your chosen provider)
- Firestore Database
- Hosting

## 3. Local preview
Install Firebase CLI:
`npm install -g firebase-tools`

Login:
`firebase login`

From this folder:
`firebase serve`

## 4. Deploy
`firebase deploy`

## 5. Important
This package keeps the existing single-page UI as the frontend. The Firebase config is a placeholder until you create/select the Firebase project. Firestore rules are a starting security baseline and should be reviewed before production.

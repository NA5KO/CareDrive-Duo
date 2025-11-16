🚗 CareDrive Duo

Bienvenue sur CareDrive Duo — Solution intelligente d’assistance et de monitoring pour conducteurs vulnérables.

Ce dépôt contient une solution prototype composée de deux applications mobiles connectées visant à améliorer la sécurité routière des conducteurs vulnérables (personnes âgées, handicap, etc.) tout en préservant leur autonomie.

## Pitch (en une phrase)

CareDrive Duo détecte les comportements à risque et les incidents à l'aide des capteurs du smartphone, alerte les proches et facilite l'intervention rapide — avec consentement et respect de la vie privée.

## Pourquoi ce projet (Hackathon)

- Problème : les conducteurs vulnérables peuvent perdre en sécurité sans perdre en autonomie.
- Solution : un duo d'applications — une installée sur le téléphone du conducteur (détection, alertes) et une pour le proche (monitoring, actions d'urgence).
- Valeur Add : prototype rapide à démontrer, fort potentiel pour POC/UX tests et intégration IA légère.

## Fonctionnalités clés

CareDrive Driver (application du conducteur)
- Détection de fatigue (analyse vidéo / heuristiques)
- Détection d'accident / décélération brutale (accéléromètre / gyroscope)
- Surveillance de vitesse et déviation d'itinéraire (GPS)
- Enregistrement/streaming sécurisé en cas d'incident
- Alertes différenciées : avertissement, critique, envoi d'alerte au proche
- Contrôles de confidentialité et consentement explicite

CareDrive Guardian (application du proche)
- Visualisation de la position et de l'état en temps réel
- Réception d'alertes et historique d'incidents
- Possibilité d'appeler les services d'urgence ou d'envoyer de l'assistance
- Demande d'accès caméra temporaire (avec approbation du conducteur)

## Prototype / Architecture (vue synthétique)

Smartphone (Conducteur)  <=>  Backend sécurisé (WebSocket / REST)  <=>  Smartphone (Proche)

- Composants typiques : GPS, caméras, accéléromètre/gyroscope, microphone (optionnel)
- Transport temps réel : WebSocket / MQTT
- Traitement local : détection embarquée + règles (préserver la vie privée)
- Backend : gestion d'événements, journal d'alertes, authentification

## Technologies envisagées

- Mobile : Flutter ou React Native (prototype multi-plateforme)
- Backend : Node.js / Python (FastAPI) ou autre selon l'équipe
- IA / Vision : MediaPipe / modèles légers pour détection d'yeux/visage
- Communication temps réel : WebSocket
- Stockage : base légère (Postgres / Firebase) selon besoin

> Remarque : le dépôt actuel est un prototype conceptuel —

## Vie privée & éthique

- Consentement explicite obligatoire avant toute capture caméra.
- Minimisation des données : ne stocker que ce qui est nécessaire.
- Chiffrement des données sensibles en transit et au repos.
- Transparence : boutons et notifications clairs pour le conducteur.


## Contacts / Équipe

- Équipe Hackathon : Arij Thabet, Sabaa Abdennabi, Farah Trigui, Nourhene Khechine, Amine Yahya
- Contact principal : arijthabet01@gmail.com

---

Merci d'avoir regardé CareDrive Duo.

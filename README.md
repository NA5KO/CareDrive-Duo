🚗 CareDrive Duo – README
🧠 CareDrive Senior & CareDrive Guardian

Solution intelligente de sécurité routière pour conducteurs vulnérables

📘 Description du projet

CareDrive Duo est une double application mobile dédiée à la protection des conducteurs âgés, fragiles ou présentant des besoins spécifiques.
Elle exploite uniquement les capteurs d’un smartphone pour analyser le comportement de conduite, détecter les risques et alerter un proche de confiance en temps réel.

🎯 Mission : Maintenir l’autonomie des conducteurs tout en renforçant la sécurité et la réactivité d’intervention.

🛑 Problématique

Les conducteurs vulnérables peuvent être sujets à :

baisse de vigilance & fatigue 💤

difficultés de navigation ou désorientation 🗺

mauvaise gestion de la vitesse 🚧

malaises ou incidents soudains 🆘

accidents sans témoin ou intervention rapide 🚑

👪 Les familles cherchent un moyen de rester rassurées sans surveillance intrusive.

🏁 Vision & Bénéfices

✔ Sécurité proactive et continue
✔ Notification immédiate au proche en cas d’incident
✔ Intervention rapide (secours, police, remorquage)
✔ Respect total de l’autonomie & consentement
✔ Réduction potentielle du risque d’accidents pour assurances

🧱 Architecture Générale

Deux applications connectées ensemble via un serveur sécurisé :

📱 CareDrive Senior (Conducteur)
⇄ Backend Sécurisé (WebSocket + API) ⇄
👨‍👩‍👦 CareDrive Guardian (Proche / Aidant)

📍 Fonctionnalités
🔹 CareDrive Senior (App Conducteur)
Domaine	Fonctionnalités
Détection des risques	vitesse excessive, déviations, arrêts fréquents
Fatigue & vigilance	analyse visage (MediaPipe) : micro-sommeil, yeux fermés
Accidents & chocs	accéléromètre + gyroscope
Alertes intelligentes	⚠️ modérées / 🚨 critiques
Actions d’urgence	appel automatique + GPS + vidéo
Vie privée maîtrisée	permissions configurables
🔹 CareDrive Guardian (App Proche)
Module	Fonctionnalités
Suivi en direct	position GPS, vitesse, batterie
Vérification visuelle	accès caméras avec autorisation
Boutons d'assistance	🚑 ambulance / 🚓 police / 🔧 dépannage
Communication	appel direct / guidage vers position
Historique	journal des alertes & incidents
🧠 Détection & Analyse
Capteur Mobile	Rôle
GPS	vitesse, trajectoire, déviation
Caméra frontale	vigilance conducteur
Caméra arrière	contexte accident
Accéléromètre/Gyroscope	collision, freinage brusque
Micro (optionnel)	suspicion de malaise
Horloge	conduite nocturne, risque accru

➡️ IA embarquée → calcul d’un score de risque dynamique

🏗 Architecture Technique

Mobile Apps : Android / iOS (stack à définir : Flutter ou React Native recommandé)

Communication temps réel : WebSocket

Backend : API + stockage chiffré

Analyse IA : MediaPipe + règles métier

🚀 Roadmap
Phase	Durée	Livrables
Phase 1	3–5 jours	UI/UX + tracking GPS + communication base
Phase 2	5–7 jours	fatigue + arrêts + monitoring proche
Phase 3	Finalisation	urgences, enregistrements vidéo, tests réels
🔐 Confidentialité & Consentement

Autorisation explicite pour chaque capteur

Accès caméra accepté par le conducteur (sauf situation critique)

Données chiffrées et minimisées

Respect total du RGPD

👥 Contribution

Contributions ouvertes 🎯
Créer une issue ou une pull request pour proposer des ajouts ou correctifs.

📄 Licence

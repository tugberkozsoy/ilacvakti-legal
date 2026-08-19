---
layout: default
title: Politique de Confidentialité
permalink: /privacy-fr/
---

# MedTime (İlaçVakti) — Politique de Confidentialité

**Dernière mise à jour :** 19 août 2026

MedTime (İlaçVakti) est une application mobile développée par le Pharmacien **Mehmet Tuğberk Özsoy**, conçue pour aider les utilisateurs à suivre leurs médicaments. Votre vie privée est notre priorité absolue ; cette politique explique de manière transparente quelles données sont traitées et de quelle façon.

Autres langues : [English](/ilacvakti-legal/privacy-en/) · [Türkçe](/ilacvakti-legal/privacy-tr/)

---

## 1. Données Non Collectées

MedTime ne collecte **pas** d'identifiants personnels (nom, e-mail, téléphone, numéro d'identité, date de naissance, etc.) auprès des utilisateurs, ne les envoie pas à nos serveurs et ne les partage pas avec des tiers. Aucune création de compte n'est requise ; l'application fonctionne entièrement de manière **anonyme**.

Liste détaillée des données non collectées :
- ❌ Régies publicitaires, profilage ou suivi inter-applications (pour la mesure publicitaire sur l'App Store, voir la Section 5)
- ❌ Services d'analyse tiers (Google Analytics, Facebook Pixel, etc.)
- ❌ Données de localisation
- ❌ Contacts, calendrier
- ❌ Conservation d'enregistrements audio (le microphone n'est activé que pour la saisie vocale facultative, voir 3.6)
- ❌ Création de compte, e-mail, téléphone
- ❌ Les données Apple Santé ne sont **jamais lues** (pour la synchronisation optionnelle en écriture seule, voir 3.5)

---

## 2. Stockage Local (Données Conservées sur Votre Appareil)

Toutes les informations que vous saisissez sont stockées **uniquement dans la mémoire interne de votre appareil** :

- Noms des médicaments, dosages, heures de rappel
- Noms de profil (noms que vous fournissez) et photo de profil facultative
- Informations sur le stock de médicaments et photos
- Historique de traitement, journaux des prises/oublis
- Données de séries (streaks) et de badges
- Rapports de santé et notes ajoutés manuellement
- Préférences de thème, de langue, de son de notification et de paramètres

Lorsque vous supprimez l'application, toutes ces données sont supprimées avec votre appareil.

---

## 3. Autorisations

### 3.1 Notifications
L'autorisation de notification est demandée pour les rappels de médicaments. Les notifications sont planifiées **localement sur votre appareil** ; aucune connexion à un serveur n'est impliquée.

### 3.2 Caméra
L'accès à la caméra est demandé uniquement sur l'écran *« Ajouter un médicament »*, afin de scanner les codes-barres/QR codes des boîtes de médicaments ou de prendre des photos des médicaments. Les images de la caméra ne sont pas envoyées à un serveur.

### 3.3 Photos
L'accès facultatif à la photothèque est demandé si vous souhaitez ajouter des photos de médicaments ou de profil. Les photos sélectionnées sont copiées uniquement dans le dossier interne de l'application sur votre appareil.

### 3.4 Consultation de la Base de Données de Médicaments
Lorsque vous scannez le code-barres/QR code d'une boîte de médicament ou que vous recherchez un médicament par son nom, seul **ce code-barres/code produit ou le nom du médicament** est envoyé à un service officiel de base de données de médicaments afin de récupérer le nom et les détails du médicament (notice, conditionnement, date de péremption, etc.). Le service utilisé dépend de la région de votre appareil : **NosyAPI** (Turquie), la base de données **U.S. FDA openFDA** (États-Unis) ou **AEMPS CIMA** (Espagne). Aucune information personnelle (votre nom, vos données de profil, vos données de santé, vos photos ou les images de la caméra) n'est incluse dans cette requête — seul le code scanné ou le terme de recherche est transmis. Cette fonctionnalité est facultative ; si vous ne l'utilisez pas, aucune donnée n'est envoyée.

Vous pouvez révoquer les autorisations à tout moment via iOS *Réglages &gt; MedTime*.

### 3.5 Apple Santé (HealthKit) — Écriture optionnelle
Les utilisateurs Premium peuvent activer *Réglages → Enregistrer dans Apple Santé* afin que les mesures de **tension artérielle, glycémie et pouls** saisies dans l'app soient **également écrites** dans l'app Santé d'Apple. Cette fonction est **entièrement optionnelle** et **désactivée par défaut**.

- İlaçVakti ne **lit jamais** vos données Santé ; l'accès est **en écriture seule** et approuvé explicitement via l'écran d'autorisation iOS.
- Seules les mesures de **votre propre profil** sont écrites ; les profils des membres de la famille ne sont jamais synchronisés.
- Les données vont directement dans le stockage Santé de votre appareil ; **rien n'est envoyé à un serveur**. Vos données Santé sont chiffrées par Apple.
- Si vous supprimez ou modifiez une mesure dans l'app, sa copie écrite dans Santé est mise à jour/supprimée en conséquence.
- Vous pouvez révoquer l'accès à tout moment via iOS *Réglages → Santé → Accès aux données et appareils → İlaçVakti*.
- Les données de santé ne sont jamais utilisées à des fins publicitaires, marketing ou analytiques (conforme à la règle 5.1.3 de l'App Store).

### 3.6 Microphone et reconnaissance vocale — Facultatif
En touchant l'icône du microphone sur l'écran de mesure, vous pouvez saisir votre tension ou votre glycémie **en parlant**. Cette fonction est **entièrement facultative** ; le microphone n'est jamais activé tant que vous ne touchez pas cette icône.

- Votre voix est transcrite **sur votre appareil** ; l'application **impose** la reconnaissance vocale sur l'appareil d'iOS. **Aucun son n'est envoyé à un serveur** — la fonction marche aussi en mode avion.
- **Aucun enregistrement audio n'est conservé.** Une fois la parole transcrite, les données audio ne sont pas stockées ; seuls les nombres reconnus sont inscrits dans les champs affichés.
- La valeur reconnue **n'est pas enregistrée directement** : elle est inscrite dans le champ et n'est consignée que lorsque vous l'avez vérifiée et que vous appuyez sur **Enregistrer**.
- Le microphone n'est actif que sur cet écran et uniquement lorsque vous le lancez ; aucune écoute en arrière-plan n'a lieu.
- Vous pouvez révoquer l'autorisation à tout moment via iOS *Réglages &gt; MedTime*.

---

## 4. Rapports de Plantage (Sentry)

Pour améliorer la stabilité de l'application, des rapports de plantage anonymes sont collectés via le service **Sentry**.

**Collecté :**
- Horodatage du plantage, modèle de l'appareil, version iOS, version de l'application
- Message d'erreur et trace technique de la pile (stack trace)
- Contexte technique précédant le plantage (par ex. écrans ouverts)

**Non collecté :**
- Nom d'utilisateur, e-mail, adresse IP (`sendDefaultPii` désactivé)
- Captures d'écran, données personnelles de médicaments, données de santé
- Photos ou contenus de rapports

Les données Sentry sont utilisées uniquement pour l'amélioration de l'application ; **jamais** à des fins de marketing ou de publicité. Les données Sentry sont conservées jusqu'à **90 jours**.

Politique de confidentialité de Sentry : <https://sentry.io/privacy/>

---

## 5. Abonnement Premium et RevenueCat

MedTime propose un **abonnement Premium** facultatif :

| Formule | Prix | Fonctionnalités |
|---|---|---|
| Mensuel | 3,99 € | Renouvellement automatique |
| Annuel | 29,99 € | Inclut un **essai gratuit de 7 jours**, renouvellement automatique |
| À vie | 49,99 € | **Paiement unique** — il ne s'agit pas d'un abonnement, aucun renouvellement |

> Les montants ci-dessus correspondent à l'App Store de la zone euro (en CHF pour la Suisse). **Les prix varient selon le pays** ; l'App Store affiche le montant exact dans votre devise locale avant la validation de l'achat.

### Gestion de l'Abonnement
- Les abonnements se renouvellent automatiquement ; le paiement est prélevé sur votre compte iTunes s'il n'est pas annulé au moins **24 heures** avant la fin de la période en cours.
- Annuler : iOS *Réglages → Apple ID → Abonnements*.
- Le **Partage familial** est activé — un abonnement peut être partagé avec jusqu'à 5 membres de la famille.
- Les paiements sont traités par Apple ; MedTime n'a aucun accès aux informations de carte bancaire.

### Accès Gratuit à Vie pour les Premiers Utilisateurs
Les utilisateurs ayant installé la version **2.0.1 (build 5) ou antérieure** bénéficient automatiquement d'un accès **Premium gratuit à vie**. Ceci est vérifié de manière anonyme sur l'appareil à l'aide du champ `originalApplicationVersion` du reçu Apple.

### RevenueCat (Validation de l'Abonnement)
Le service **RevenueCat** est utilisé pour valider l'état de l'abonnement. Un identifiant anonyme (App User ID) dérivé de votre Apple ID ainsi que les données du reçu Apple sont envoyés à RevenueCat. Votre nom, votre e-mail ou vos coordonnées ne sont **pas partagés**.

Politique de confidentialité de RevenueCat : <https://www.revenuecat.com/privacy/>

### Mesure Publicitaire (Apple Search Ads)
MedTime diffuse occasionnellement des annonces sur l'App Store. Afin de mesurer quelle annonce vous a amené vers l'application, un *jeton d'attribution* généré par Apple **au moment de l'installation** est transmis à RevenueCat, qui interroge Apple pour savoir si l'installation provient d'une annonce.

- Ce jeton **n'est pas votre identifiant publicitaire (IDFA)** et ne vous identifie ni vous ni votre appareil. C'est pourquoi l'écran iOS de *Transparence du suivi des apps* n'est pas affiché : aucun suivi inter-applications n'est effectué.
- Apple ne renvoie que des informations **au niveau de la campagne**. Elles ne sont **jamais associées** à votre nom, votre profil, vos médicaments ou vos données de santé.
- L'opération n'a lieu **qu'une seule fois, à l'installation** ; votre utilisation de l'application n'est ensuite pas suivie à des fins publicitaires.
- Son unique finalité est de vérifier que le budget publicitaire est bien employé ; elle n'est **pas** utilisée pour vous cibler ni pour vendre des données.

### Conditions d'Utilisation
Le CLUF standard d'Apple s'applique : <https://www.apple.com/legal/internet-services/itunes/dev/stdeula/>

---

## 6. Partage des Données

MedTime ne **partage pas les données des utilisateurs avec un tiers, ne les vend pas et ne les utilise pas à des fins de marketing**. Les seules exceptions sont :

- Les consultations de la base de données de médicaments décrites dans la Section 3.4 (NosyAPI / U.S. FDA openFDA / AEMPS CIMA) — seul le code scanné ou le nom du médicament recherché est transmis ; il ne contient aucune donnée personnelle.
- Les rapports de plantage anonymes décrits dans la Section 4 (Sentry).
- Les données anonymes de validation d'abonnement ainsi que le jeton d'attribution publicitaire non identifiant décrits dans la Section 5 (RevenueCat + Apple).

---

## 7. Vos Droits au Titre du RGPD (Utilisateurs de l'UE)

Si vous résidez dans l'UE, en vertu du Règlement Général sur la Protection des Données (RGPD), vous disposez des droits d'**accès, de rectification, d'effacement, d'opposition au traitement et de portabilité des données**. Nos bases légales sont : la nécessité pour la fourniture du service (Article 6(1)(b)) et l'intérêt légitime pour le signalement des erreurs (Article 6(1)(f)).

---

## 8. Vos Droits au Titre de la KVKK Turque

En vertu de l'article 11 de la loi turque sur la protection des données personnelles (KVKK), vous disposez de droits incluant : savoir si vos données sont traitées, demander des informations, demander la rectification ou la suppression, connaître les tiers auxquels les données ont été transférées, vous opposer aux résultats d'un traitement automatisé et réclamer une indemnisation. Pour exercer ces droits, contactez <ilacvaktidestek@gmail.com>. Les demandes reçoivent une réponse sous **30 jours**.

---

## 9. Confidentialité des Enfants

L'application est classée **4+**. Aucune donnée n'est sciemment collectée auprès d'enfants de moins de 13 ans. Si un parent utilise l'application pour ajouter un profil d'enfant (membre de la famille), les données de ce profil restent stockées localement sur l'appareil uniquement.

---

## 10. Sécurité des Données

Comme vos données sont principalement stockées sur votre appareil, elles sont protégées par le chiffrement matériel d'iOS (Secure Enclave). Les communications avec les services tiers sont chiffrées via HTTPS.

---

## 11. Modifications de Cette Politique

Nous pouvons mettre à jour cette politique de temps à autre. Les modifications importantes seront annoncées par une notification dans l'application ou via les notes de version. Veuillez consulter régulièrement la date de *Dernière mise à jour*.

---

## 12. Contact

E-mail : <ilacvaktidestek@gmail.com>

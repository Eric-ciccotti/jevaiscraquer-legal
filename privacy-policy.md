# Politique de Confidentialité — Je Vais Craquer

**Dernière mise à jour : 20 avril 2026**

## Introduction

Je Vais Craquer (ci-après "l'Application") est une application iOS d'aide post-rupture amoureuse développée par Eric Ciccotti (ci-après "le Développeur"). La présente Politique de Confidentialité a pour objet de vous informer sur la manière dont vos données personnelles sont collectées, utilisées et protégées conformément au Règlement Général sur la Protection des Données (RGPD) et aux lois applicables en matière de protection des données.

Le Développeur s'engage à protéger votre vie privée. L'Application a été conçue selon le principe de **privacy by design** : vos données personnelles ne quittent pas votre écosystème Apple. Aucune donnée n'est transmise à un serveur du Développeur.

---

## 1. Données collectées

L'Application vous demande de saisir les informations suivantes lors de la configuration initiale et de l'utilisation :

- **Prénom de l'utilisateur** : pour personnaliser les messages de soutien.
- **Genre de l'utilisateur** (masculin / féminin / non-binaire) : pour adapter les accords grammaticaux.
- **Prénom de l'ex-partenaire** : pour personnaliser les rituels et exercices.
- **Genre de l'ex-partenaire** (masculin / féminin / non-binaire) : pour adapter les accords grammaticaux.
- **Date de la rupture** : pour calculer le nombre de jours écoulés et adapter le contenu.
- **Préférences émotionnelles** : ce qui vous manque le plus, le moment le plus difficile de la journée.
- **Message personnel de motivation** : un texte que vous rédigez pour vous-même.
- **Lettres écrites** : les lettres rédigées dans le cadre du module d'urgence ou du module "ex m'a écrit".
- **Historique d'humeur** : les entrées quotidiennes d'humeur et notes optionnelles associées.
- **Journal personnel** : les textes rédigés dans le journal matin/soir.
- **Statistiques d'utilisation locale** : nombre d'urgences déclenchées, streak de jours sans contact, rituels effectués, missions complétées.
- **Date d'installation** : pour suivre la progression dans le parcours de l'Application.

**Aucune de ces données n'est de nature médicale ou clinique.** L'Application n'est pas un dispositif médical.

---

## 2. Stockage et synchronisation des données

### 2.1 Stockage local

Les données saisies sont stockées sur votre appareil dans le système de stockage natif iOS (UserDefaults), au sein de la sandbox applicative.

- **Aucune donnée n'est transmise à un serveur du Développeur.**
- **Aucune base de données externe** n'est utilisée pour vos données personnelles.

### 2.2 Synchronisation iCloud entre vos appareils

Pour permettre la continuité de votre parcours entre vos appareils Apple (iPhone, iPad) connectés au même identifiant Apple, l'Application utilise **iCloud Key-Value Store** (NSUbiquitousKeyValueStore), un service de synchronisation fourni par Apple.

**Données synchronisées via iCloud** :

- Prénom de l'utilisateur et de l'ex-partenaire
- Genres (utilisateur et ex-partenaire)
- Date de la rupture, message personnel, préférences émotionnelles
- Historique d'humeur et notes associées
- Journal personnel (entrées matin / soir)
- Lettres écrites
- Statistiques d'utilisation (rituels complétés, urgences, compteurs de rituels spécifiques)
- Date d'installation de l'Application
- État d'avancement de l'onboarding

**Important — Persistance au-delà de la désinstallation :**

Les données synchronisées via iCloud Key-Value Store sont associées à votre compte iCloud personnel et **persistent même après la désinstallation de l'Application**. Elles sont automatiquement restaurées si vous réinstallez l'Application, ou si vous l'utilisez sur un autre de vos appareils Apple. Cette fonctionnalité garantit la continuité de votre parcours, essentielle dans un contexte d'accompagnement émotionnel.

**Apple est sous-traitant** pour ce service. La synchronisation iCloud est régie par les [conditions de confidentialité d'Apple](https://www.apple.com/legal/privacy/).

**Comment désactiver la synchronisation iCloud :**

- **Réglages iOS** → **[Votre nom]** → **iCloud** → **Applications utilisant iCloud** → désactiver **Je Vais Craquer**.

**Comment effacer les données synchronisées iCloud :**

- **Réglages iOS** → **[Votre nom]** → **iCloud** → **Gérer le stockage du compte** → **Je Vais Craquer** → **Supprimer les données**.

---

## 3. Analytique anonyme (TelemetryDeck)

L'Application utilise **TelemetryDeck**, un service d'analytique respectueux de la vie privée, pour comprendre comment l'Application est utilisée de façon globale et l'améliorer.

- TelemetryDeck **ne collecte aucune donnée personnelle identifiable**.
- Les événements envoyés sont **anonymisés et agrégés** : ils indiquent uniquement qu'une fonctionnalité a été utilisée, sans aucune information permettant d'identifier l'utilisateur.
- Aucun prénom, aucun contenu de lettre, aucune donnée d'humeur ni aucune donnée de journal n'est transmis.
- Les données anonymes transitent par les serveurs de TelemetryDeck (Allemagne, conforme RGPD). Pour en savoir plus : [telemetrydeck.com/privacy](https://telemetrydeck.com/privacy/).

---

## 4. Partage de données avec des tiers

L'Application **ne partage aucune donnée personnelle avec des tiers** autres qu'Apple (pour la synchronisation iCloud décrite à la section 2.2) et TelemetryDeck (pour les statistiques anonymes décrites à la section 3).

- Pas de traceurs publicitaires.
- Pas de SDK collectant des données personnelles.
- Pas de publicités.
- Pas de partage avec des réseaux sociaux.

---

## 5. Utilisation du microphone

L'Application peut demander l'accès au microphone dans le cadre du rituel de la flamme (détection du souffle de l'utilisateur).

- L'accès au microphone est **facultatif** et soumis à votre autorisation explicite via la demande de permission iOS.
- **Aucun enregistrement audio n'est effectué.**
- **Aucune donnée audio n'est stockée ni transmise.**
- Le signal du microphone est traité **uniquement en temps réel et en local** sur votre appareil.
- Vous pouvez révoquer cette autorisation à tout moment dans Réglages > Confidentialité > Microphone.

---

## 6. Notifications

L'Application peut envoyer des notifications de rappel pour vous accompagner dans votre parcours.

- Ce sont des **notifications locales uniquement**, programmées directement sur votre appareil.
- **Aucun service de notification distant (push)** n'est utilisé.
- Vous pouvez désactiver les notifications à tout moment dans les réglages de votre appareil ou dans l'Application.

---

## 7. Achats intégrés (In-App Purchases)

L'Application propose un abonnement premium via le système d'achat intégré d'Apple (StoreKit).

- Les transactions d'achat sont **entièrement gérées par Apple**.
- Le Développeur n'a pas accès à vos informations de paiement.
- La gestion de votre abonnement s'effectue via votre compte Apple. Pour plus d'informations, consultez la [politique de confidentialité d'Apple](https://www.apple.com/legal/privacy/).

---

## 8. Compte utilisateur

L'Application **ne nécessite aucune création de compte**, aucune inscription et aucune connexion. Aucune adresse email, mot de passe ou identifiant n'est collecté par l'Application. Les données synchronisées iCloud (section 2.2) sont associées à votre identifiant Apple, géré par Apple.

---

## 9. Données des mineurs

L'Application n'est pas destinée aux enfants de moins de 16 ans. Nous ne collectons pas sciemment de données personnelles de mineurs. Si vous êtes un parent et pensez que votre enfant utilise l'Application, contactez-nous.

---

## 10. Vos droits (RGPD)

Conformément au RGPD, vous disposez des droits suivants :

- **Droit d'accès** : toutes vos données sont visibles directement dans l'Application.
- **Droit de rectification** : vous pouvez modifier vos informations à tout moment dans les réglages de l'Application.
- **Droit à l'effacement** : vous pouvez effacer vos données par les moyens suivants :
  1. **Désinstaller l'Application** : supprime les données locales de l'appareil.
  2. **Effacer les données iCloud synchronisées** : Réglages iOS → [Votre nom] → iCloud → Gérer le stockage du compte → Je Vais Craquer → Supprimer les données.
  3. **Effacement complet** : les deux étapes ci-dessus combinées suppriment définitivement l'intégralité de vos données personnelles de l'écosystème Apple.
- **Droit à la portabilité** : les données étant stockées dans votre écosystème Apple, elles sont déjà en votre possession.
- **Droit d'opposition** : aucun traitement automatisé ou profilage n'est effectué sur vos données personnelles.

---

## 11. Sécurité

Les données sont protégées par les mécanismes de sécurité natifs d'iOS (chiffrement de l'appareil, sandbox applicative) et d'iCloud (chiffrement en transit et au repos). Le Développeur ne peut pas accéder à vos données puisqu'elles ne transitent jamais par son infrastructure.

---

## 12. Modifications de cette politique

Le Développeur se réserve le droit de modifier la présente Politique de Confidentialité. Toute modification sera publiée sur cette page. La date de dernière mise à jour en haut de ce document sera actualisée en conséquence.

---

## 13. Contact

Pour toute question relative à la présente Politique de Confidentialité :

- **Email** : [eric.ciccotti@gmail.com](mailto:eric.ciccotti@gmail.com)
- **Développeur** : Eric Ciccotti

---

*Cette politique de confidentialité est effective à compter du 20 avril 2026.*

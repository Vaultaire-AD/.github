# Vaultaire

![Vaultaire Logo](/profile/images/vaultaire_logo.svg)

> **Un annuaire moderne et sécurisé – Une alternative sérieuse à Active Directory**

---

## 🚀 Présentation

**Vaultaire** est un projet open-source visant à développer un concurrent sérieux à *Active Directory*, tout en intégrant des pratiques de cybersécurité modernes et robustes.  
Nous repensons la gestion des annuaires pour les adapter aux besoins actuels : sécurité renforcée, intégration fluide avec les outils modernes et simplicité d’administration.

Notre objectif : **moderniser les systèmes d’authentification et d’annuaire**, tout en offrant des fonctionnalités avancées comme **SSO**, **MFA** et un haut niveau de compatibilité multi-plateforme.

---

## 🔐 Domaines d’activité

- **Gestion des identités** : utilisateurs, groupes, droits, rôles.
- **Sécurité avancée** : authentification forte, MFA, SSO.
- **Services réseau intégrés** : DNS interne, LDAP compatible Keycloak.
- **Compatibilité Linux & Windows** : gestion des droits et comptes de manière unifiée.
- **Interopérabilité** : intégration avec des environnements conteneurisés et orchestrés.

---

## 🛠️ Stack technique

- **Langages** : Go, C (modules PAM)
- **Base de données** : MariaDB
- **Conteneurisation & orchestration** : Docker, Kubernetes
- **Interopérabilité** : compatibilité LDAP, intégration Keycloak

---

## 📦 Projets phares

### 🔹 `vaultaire_AD` *(Alpha)*
Un service écrit en Go pour la gestion centralisée des utilisateurs et droits sur Linux et Windows, avec :

- Gestion des comptes et groupes avec droits sudo ou restreints (Rocky Linux).
- DNS interne intégré.
- Serveur LDAP pouvant être lié à Keycloak.
- Stockage des données en **SQL** pour une meilleure persistance et sécurité.
- **Statut** : Fonctionnel en alpha, **à ne pas utiliser en production**.

---

## 💡 Philosophie

Nous croyons en :

- **La collaboration** : développement ouvert et transparent.
- **La sécurité** : intégrée dès la conception.
- **La modernisation** : pas de réinvention inutile, mais mise à jour et optimisation des technologies existantes.

---

## 📫 Contact

- **Email** : [contact@vaultaire.fr](mailto:contact@vaultaire.fr)
- **Site web** : *à venir*

---

> 🛡️ *Vaultaire – La gestion d'identités et d'annuaires, repensée pour l'ère moderne.*

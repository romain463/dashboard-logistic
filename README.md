# Pilotage Logistique National

Application web sécurisée — 1 seul fichier HTML, zéro serveur requis, hébergeable sur GitHub Pages.

## Déploiement GitHub Pages (3 minutes)

1. Créer un repository GitHub (public ou privé avec GitHub Pro)
2. Uploader `index.html`
3. **Settings → Pages → Source → main → / (root)**
4. Accès à `https://votre-compte.github.io/nom-repo`

## Connexions disponibles

| Méthode | Usage |
|---------|-------|
| **Identifiant + mot de passe** | Connexion standard via l'écran de login |
| **Lien direct** `?token=xxx` | Accès viewer sans mot de passe (partageable par email/Teams) |

## Compte admin par défaut

- **Identifiant** : `admin`
- **Mot de passe** : `logi2026!`

> ⚠️ Changer le mot de passe dès la première connexion via ⚙️ Admin → recréer le compte admin

## Rôles

| Rôle | Droits |
|------|--------|
| **Admin** | Tout : tableau de bord, évolution, suivi WO, préparation, import, gestion utilisateurs |
| **Viewer** | Lecture seule : tableau de bord, évolution, suivi WO, liste préparation |

## Gestion des accès (depuis ⚙️ Admin)

- Créer un compte Viewer ou Admin
- Générer un lien de partage direct (token dans l'URL)
- Suspendre / supprimer un accès
- Régénérer un token (invalide l'ancien lien)

## Import hebdomadaire (Admin uniquement)

1. Aller dans **⬆️ Import**
2. Saisir le numéro de semaine (ex: `W22`)
3. Glisser l'export BI Excel

## Stockage

Les données sont stockées dans l'**API Claude persistent storage** (partagé entre tous les utilisateurs de l'artifact) et en **localStorage** du navigateur (pour les données WO).


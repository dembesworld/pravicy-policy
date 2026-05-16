# Formulaire « Data Safety » Google Play Console — NkaSorro

Réponses prêtes à recopier dans la section **"Sécurité des données"** (Data Safety) de la Play Console.

---

## Section 1 — Collecte et partage de données

| Question | Réponse |
|---|---|
| Votre application collecte-t-elle ou partage-t-elle des types de données utilisateur requis ? | **Non** |
| Toutes les données sont-elles chiffrées en transit ? | **Sans objet** (aucune transmission) |
| Les utilisateurs peuvent-ils demander la suppression de leurs données ? | **Oui** — via la fonction "Supprimer tout l'historique" dans l'app ou par désinstallation |

---

## Section 2 — Types de données

Pour chaque catégorie de données proposée par Google, cocher **« Pas de données collectées »** :

### Localisation
- ☐ Localisation approximative — **NON**
- ☐ Localisation précise — **NON**

### Informations personnelles
- ☐ Nom — **NON**
- ☐ Adresse e-mail — **NON**
- ☐ ID utilisateur — **NON**
- ☐ Adresse — **NON**
- ☐ Numéro de téléphone — **NON**
- ☐ Race et origine ethnique — **NON**
- ☐ Convictions politiques ou religieuses — **NON**
- ☐ Orientation sexuelle — **NON**
- ☐ Autres infos perso — **NON**

### Informations financières
- ☐ Informations de paiement — **NON**
- ☐ Historique d'achat — **NON**
- ☐ Score de crédit — **NON**
- ☐ Autres infos financières — **NON**

> ⚠️ **Note importante** : bien que l'app *calcule* des montants financiers (salaire, impôt), elle ne *collecte* ni *transmet* aucune de ces données. Les calculs ne sont pas considérés comme une "collecte" au sens de Play Store car ils restent strictement locaux.

### Santé et fitness
- ☐ Santé — **NON**
- ☐ Fitness — **NON**

### Messages
- ☐ E-mails — **NON**
- ☐ SMS / MMS — **NON**
- ☐ Autres messages dans l'app — **NON**

### Photos et vidéos
- ☐ Photos — **NON**
- ☐ Vidéos — **NON**

### Fichiers audio
- ☐ Enregistrements vocaux/audio — **NON**
- ☐ Fichiers musicaux — **NON**
- ☐ Autres fichiers audio — **NON**

### Fichiers et documents
- ☐ Fichiers et documents — **NON**
  - *Bien que l'app génère des PDF, ils ne sont ni collectés ni envoyés ailleurs — ils sont créés localement à la demande de l'utilisateur.*

### Calendrier
- ☐ Événements de calendrier — **NON**

### Contacts
- ☐ Contacts — **NON**

### Activité dans l'app
- ☐ Interactions dans l'app — **NON**
- ☐ Historique de recherche dans l'app — **NON**
- ☐ Pages installées — **NON**
- ☐ Autre activité dans l'app — **NON**

### Informations et performances Web
- ☐ Historique de navigation Web — **NON**

### Informations et performances de l'application
- ☐ Journaux de plantage — **NON** (pas de Crashlytics ni équivalent)
- ☐ Diagnostics — **NON**
- ☐ Autres performances — **NON**

### Identifiants de l'appareil ou autres
- ☐ ID de l'appareil ou autre — **NON** (pas d'AAID, IDFA, etc.)

---

## Section 3 — Pratiques de sécurité

| Question | Réponse |
|---|---|
| Les données utilisateur sont-elles chiffrées en transit ? | **Sans objet** (aucune transmission de données) |
| Fournissez-vous un moyen aux utilisateurs de demander la suppression de leurs données ? | **Oui — données supprimables directement dans l'app** |
| Engagement à respecter la politique « Famille » Google Play (apps pour enfants) | **Non applicable** (app destinée aux adultes) |
| L'app a-t-elle été examinée pour les normes de sécurité MASVS / autres ? | **Non** (mais peut être déclaré "non" en toute confiance) |

---

## Section 4 — URL de la politique de confidentialité

```
https://VOTRE_DOMAINE/privacy_policy.html
```

> 📌 **À héberger** : le fichier `privacy_policy.html` doit être déployé sur une URL publique. Options recommandées (gratuites) :
> - **GitHub Pages** (`https://USERNAME.github.io/nkasorro-privacy/`)
> - **Netlify Drop** (drag-and-drop, URL immédiate)
> - **Vercel** (à partir d'un repo)
> - Un site existant que vous possédez

---

## Section 5 — Public cible

| Question | Réponse |
|---|---|
| Tranche d'âge cible | **18 ans et plus** (app fiscale destinée aux salariés) |
| L'app présente-t-elle du contenu réservé aux adultes ? | **Non** |
| Conçue pour les enfants ? | **Non** |

---

## ✅ Synthèse pour la Play Console

```
┌──────────────────────────────────────────────────┐
│  Data Safety — NkaSorro                          │
│  ───────────────────────────────                 │
│  ✓ Aucune donnée collectée                       │
│  ✓ Aucune donnée partagée                        │
│  ✓ Suppression possible (dans l'app)             │
│  ✓ Politique de confidentialité fournie          │
│  ✓ Pas de tracker, pas de pub, pas de SDK tiers │
└──────────────────────────────────────────────────┘
```

C'est le scénario le plus favorable possible pour la Play Store : Google met une étiquette verte "No data collected" sur la fiche de l'app, ce qui rassure les utilisateurs.

# Permissions par grade

{% hint style="info" %}
Ce tableau récapitule l'ensemble des permissions disponibles pour chaque grade du staff.
{% endhint %}

## Modérateur Test

> Période d'essai de 7 à 14 jours — Permissions limitées.

| Permission | Commande | Accès |
| --- | --- | --- |
| Kick | `/kick [id] [raison]` | ✅ |
| Warn | `/warn [id] [raison]` | ✅ |
| Spectate | `/spectate [id]` | ✅ |
| Ban | — | ❌ |
| Noclip | — | ❌ |
| Téléportation | — | ❌ |

---

## Modérateur

> Grade confirmé après validation de la période d'essai.

| Permission | Commande | Accès |
| --- | --- | --- |
| Kick | `/kick [id] [raison]` | ✅ |
| Warn | `/warn [id] [raison]` | ✅ |
| Spectate | `/spectate [id]` | ✅ |
| Ban temporaire | `/ban [id] [durée] [raison]` | ✅ (7j max) |
| Noclip | `/noclip` | ✅ |
| Téléportation | `/tp [id]` | ✅ |
| Bring | `/bring [id]` | ✅ |
| Freeze | `/freeze [id]` | ✅ |
| Mute | `/mute [id] [durée]` | ✅ |
| Vanish | `/vanish` | ✅ |
| Annonces | `/announce [message]` | ✅ |
| Vérifier inventaire | `/checkinv [id]` | ✅ |
| Historique joueur | `/history [id]` | ✅ |
| Give items | — | ❌ |
| Spawn véhicule | — | ❌ |
| Ban permanent | — | ❌ |

---

## Administrateur

> Toutes les permissions Modérateur + gestion avancée.

| Permission | Commande | Accès |
| --- | --- | --- |
| Toutes commandes Modérateur | — | ✅ |
| Ban permanent | `/ban [id] 0 [raison]` | ✅ |
| Unban | `/unban [id/licence]` | ✅ |
| Give items | `/give [id] [item] [qté]` | ✅ |
| Remove items | `/removeitem [id] [item] [qté]` | ✅ |
| Spawn véhicule | `/car [modèle]` | ✅ |
| Supprimer véhicule | `/dv` | ✅ |
| Heal | `/heal [id]` | ✅ |
| Armor | `/armor [id]` | ✅ |
| Revive | `/revive [id]` | ✅ |
| TP waypoint | `/tpm` | ✅ |
| Météo | `/weather [type]` | ✅ |
| Heure | `/time [hh] [mm]` | ✅ |
| Vérifier argent | `/checkmoney [id]` | ✅ |
| Set argent | `/setmoney [id] [type] [montant]` | ✅ |
| Accès txAdmin | Panel Web | ✅ |

---

## Fondateur

> Accès total et illimité.

| Permission | Accès |
| --- | --- |
| Toutes les commandes ci-dessus | ✅ |
| Restart serveur | ✅ |
| Stop / Start resources | ✅ |
| Modifier fichiers serveur | ✅ |
| Accès base de données | ✅ |
| Accès hébergement | ✅ |
| Gestion des rôles staff | ✅ |
| Décision finale | ✅ |

---

## Tableau comparatif

| Permission | Mod Test | Mod | Admin | Fondateur |
| --- | --- | --- | --- | --- |
| Kick | ✅ | ✅ | ✅ | ✅ |
| Warn | ✅ | ✅ | ✅ | ✅ |
| Spectate | ✅ | ✅ | ✅ | ✅ |
| Ban temporaire | ❌ | ✅ | ✅ | ✅ |
| Ban permanent | ❌ | ❌ | ✅ | ✅ |
| Unban | ❌ | ❌ | ✅ | ✅ |
| Noclip | ❌ | ✅ | ✅ | ✅ |
| Téléportation | ❌ | ✅ | ✅ | ✅ |
| Bring | ❌ | ✅ | ✅ | ✅ |
| Freeze | ❌ | ✅ | ✅ | ✅ |
| Mute | ❌ | ✅ | ✅ | ✅ |
| Vanish | ❌ | ✅ | ✅ | ✅ |
| Vérifier inventaire | ❌ | ✅ | ✅ | ✅ |
| Give items | ❌ | ❌ | ✅ | ✅ |
| Remove items | ❌ | ❌ | ✅ | ✅ |
| Spawn véhicule | ❌ | ❌ | ✅ | ✅ |
| Heal / Armor / Revive | ❌ | ❌ | ✅ | ✅ |
| Météo / Heure | ❌ | ❌ | ✅ | ✅ |
| Set argent | ❌ | ❌ | ✅ | ✅ |
| Accès txAdmin | ❌ | ❌ | ✅ | ✅ |
| Restart serveur | ❌ | ❌ | ❌ | ✅ |
| Gérer resources | ❌ | ❌ | ❌ | ✅ |
| Modifier config | ❌ | ❌ | ❌ | ✅ |
| Accès BDD | ❌ | ❌ | ❌ | ✅ |

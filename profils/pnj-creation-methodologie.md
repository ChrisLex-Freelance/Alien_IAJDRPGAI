# MÉTHODOLOGIE DE CRÉATION DE PNJ HUMAIN

Cette méthodologie structure la création des PNJ humains autour d'un **template de rôle** (voir [pnj-templates.md](pnj-templates.md)) ajusté selon un **niveau d'expérience** : **Junior**, **Expert** ou **Senior**.

Elle s'appuie sur les valeurs de référence d'un personnage joueur (14 points d'attributs, 10 points de compétences, 2 talents) utilisées par le [score d'Antagonisme](../rules/score-antagonisme.md).

---

## PRINCIPE GÉNÉRAL

Un PNJ se construit en deux couches :

1. **Le rôle** — qui il est et ce qu'il sait faire (template : attributs répartis, compétences de spécialité, équipement).
2. **Le niveau** — où il en est dans sa carrière (Junior / Expert / Senior), qui module la puissance du PNJ **sans changer son identité**.

> **Règle d'or** : le niveau ne modifie jamais la répartition *relative* des attributs ni la liste des compétences. Il ajoute de la puissance sur les points forts du rôle, pas de nouvelles spécialités.

---

## ÉTAPE 1 — CHOISIR LE TEMPLATE DE RÔLE

Partez d'un template du [tableau des PNJ](pnj-templates.md), ou créez-en un en respectant le budget **Expert** :

| ÉLÉMENT | BUDGET EXPERT (RÉFÉRENCE) |
|---|---|
| Attributs | **14 points** répartis (For/Agi/Esp/Emp/San), maximum 5 par attribut, minimum 2* |
| Compétences | **10 points** répartis, maximum 4 par compétence |
| Talents | **2 talents** cohérents avec le rôle |
| Équipement | Selon le rôle et la fiction |

\* Sauf exceptions fictionnelles justifiées (androïdes : attributs hors norme ; machine à tuer : Emp 1 ; etc.). Une anomalie forte est un signal d'antagonisme, pas un bug.

Les attributs indiqués dans les templates existants (For 4, Agi 3, etc.) sont déjà des **valeurs absolues d'attribut**, pas des points à répartir : un total de 14 correspond à un PNJ Expert.

---

## ÉTAPE 2 — CHOISIR LE NIVEAU : JUNIOR / EXPERT / SENIOR

| NIVEAU | IDÉE NARRATIVE | ATTRIBUTS | COMPÉTENCES | TALENTS | SCORE D'ANTAGONISME CIBLE |
|---|---|---|---|---|---|
| **Junior** | Débutant, newly promoted, encore vert | **12 points** (−2 vs référence) | **8 points** (−2) | **1 talent** (−1) | **−25** |
| **Expert** | Confirmé, valeur de référence d'un PJ | **14 points** (référence) | **10 points** (référence) | **2 talents** (référence) | **0** |
| **Senior** | Vétéran, référence du secteur, boss de fin d'acte | **16 points** (+2) | **12 points** (+2) | **3 talents** (+1) | **+25** |

Le score d'Antagonisme se calcule selon la [méthode officielle](../rules/score-antagonisme.md) : (écart d'attributs + écart de compétences + écart de talents) × 5.

---

## ÉTAPE 3 — APPLIQUER LE NIVEAU AU TEMPLATE

### ATTRIBUTS

- **Junior** : retirez 1 point aux **deux attributs les plus élevés** du template (un attribut ne descend jamais sous 2 pour un humain).
- **Expert** : ne changez rien (budget de référence).
- **Senior** : ajoutez +1 aux **deux attributs les plus cohérents avec le rôle** (ex. Esp/Emp pour un dirigeant, For/Agi pour un soldat). Un attribut humain ne dépasse pas 5.

### COMPÉTENCES

- **Junior** : retirez 1 point aux **deux compétences les plus élevées** du template (minimum 0 : une compétence peut disparaître de la fiche).
- **Expert** : ne changez rien.
- **Senior** : ajoutez +1 aux **deux compétences signature** du rôle (ex. Manipulation et Commandement pour un dirigeant). Aucune compétence humaine ne dépasse 5.

### TALENTS

- **Junior** : gardez **1 talent** (le plus représentatif du rôle).
- **Expert** : gardez **2 talents**.
- **Senior** : **3 talents** — ajoutez un talent tiers qui reflète l'expérience accumulée (leadership, réseau, sang-froid), à prendre dans les [talents généraux](../talents/general.md).

### ÉQUIPEMENT

- **Junior** : équipement de base, standard, parfois usé.
- **Expert** : équipement du template.
- **Senior** : ajoutez **un objet signature** de qualité supérieure (arme de service personnalisée, hardware haut de gamme, protections améliorées) — c'est souvent sa récompense de fin de combat.

---

## ÉTAPE 4 — HABILLER LE PNJ

Pour donner de la profondeur, tirez ou choisissez :

- [Apparence](../random-tables/apparence.md) (cheveux, regard, sourire)
- [Comportements](../random-tables/comportements.md) (tics et manies)
- [Opinions](../random-tables/opinions.md) (sur les corporations, l'UPP, la religion, etc.)
- Un **Camarade** et un **Rival** au sein de l'organisation
- Le **score d'Antagonisme** final, à afficher sur la fiche comme indication de difficulté

---

## TABLEAU RÉCAPITULATIF

| ÉTAPE | ACTION | SOURCE |
|---|---|---|
| 1 | Choisir le template de rôle | [pnj-templates.md](pnj-templates.md) |
| 2 | Choisir le niveau (Junior/Expert/Senior) | Tableau ci-dessus |
| 3 | Ajuster attributs, compétences, talents, équipement | Règles de l'étape 3 |
| 4 | Habiller (apparence, comportements, opinions) | [random-tables/](../random-tables/) |
| 5 | Calculer le score d'Antagonisme | [rules/score-antagonisme.md](../rules/score-antagonisme.md) |

---

## EXEMPLE COMPLET : MARSHAL DE LA FRONTIÈRE

Template **Expert** (référence) : For 5, Agi 4, Esp 4, Emp 4, San 2 — Combat rapproché 4, Combat à distance 3, Mobilité 1, Observation 1, Manipulation 1, Soins médicaux 1 — Talents : Investigateur — Couteau pliant, fusil à pompe, menottes.

**Marshal Junior** (−25 d'antagonisme) :
- Attributs : For **4**, Agi 4, Esp 4, Emp 4, San 2 → retire 1 aux deux plus élevés (For et Agi/Esp/Emp au choix narratif)
- Compétences : Combat rapproché **3**, Combat à distance **2** (−1 aux deux plus hautes)
- Talent : **Investigateur** (le seul, le plus représentatif)
- Équipement : standard, le fusil est une arme de service usée

**Marshal Senior** (+25 d'antagonisme) :
- Attributs : For **5**, Agi 4, Esp 4, Emp **4**, San 2 → +1 sur les points forts du rôle
- Compétences : Combat rapproché **5**, Combat à distance **4** (+1 aux deux signatures)
- Talents : **Investigateur, Bons réflexes, Commandant de patrouille** (talent d'expérience)
- Équipement : + un objet signature — un fusil à pompe gravé, trophée de vingt ans de service

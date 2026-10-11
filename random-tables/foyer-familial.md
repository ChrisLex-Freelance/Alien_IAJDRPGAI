---
type: random_table
title: Environnement familial
game: Alien RPG
language: fr
category: character_background
description: Tables pour générer l'environnement familial d'un personnage, enrichissant l'interprétation et le rôleplay
usage: "Lancer 1D6 dans chacune des six catégories ou choisir les résultats"
tables:
  - name: "Parents"
    dice: D6
    count: 6
    description: "Situation des parents du personnage"
    entries:
      - id: 1
        text: "Orphelin, aucun parent vivant."
        interpretation: "Le personnage a appris à se débrouiller seul. Il peut être indépendant et méfiant, ou rechercher des figures parentales de substitution."
      - id: 2-3
        text: "Un parent vivant, l'autre est décédé ou disparu."
        interpretation: "La perte, l'abandon ou la disparition ont marqué ses relations. Il peut protéger férocement le parent restant, lui en vouloir ou chercher la vérité sur ce qui s'est passé."
      - id: 4-6
        text: "Deux parents vivants."
        interpretation: "Une enfance stable peut cacher une pression pour réussir, des attentes contradictoires ou une loyauté familiale difficile à concilier avec la vie du personnage."
  - name: "Relation avec les parents"
    dice: D6
    count: 6
    description: "Qualité de la relation avec les parents"
    entries:
      - id: 1
        text: "Relations tendues ou distantes."
        interpretation: "Le personnage porte des non-dits, de la colère ou de l'indifférence. Il peut éviter les confrontations ou les provoquer pour obtenir enfin une réponse."
      - id: 2-4
        text: "Relations normales, avec quelques conflits occasionnels."
        interpretation: "L'affection et les désaccords coexistent. Le personnage peut être pragmatique sans idéaliser ni rejeter l'influence parentale."
      - id: 5-6
        text: "Relations très proches et soutenues."
        interpretation: "La famille apporte confiance et stabilité, mais ses critiques pèsent lourd. Le personnage peut être prêt à prendre des risques pour la rendre fière ou la protéger."
  - name: "Frères et sœurs"
    dice: D6
    count: 6
    description: "Nombre de frères et sœurs"
    entries:
      - id: 1-2
        text: "Aucun frère ou sœur."
        interpretation: "Le personnage connaît la solitude ou l'autonomie et peut chercher une famille de substitution parmi les membres du groupe."
      - id: 3-4
        text: "Un frère ou une sœur."
        interpretation: "Le frère ou la sœur peut être un modèle, un rival, une personne à protéger ou un lien encore maintenu par des messages et des dettes."
      - id: 5
        text: "Deux frères et/ou sœurs."
        interpretation: "La coopération, la compétition et les alliances ont probablement façonné le personnage. La loyauté familiale peut entrer en conflit avec la mission."
      - id: 6
        text: "Trois frères et/ou sœurs ou plus."
        interpretation: "Le personnage a dû occuper une place identifiable: leader, médiateur, oublié, protecteur ou rebelle. Cette place peut se reproduire dans le groupe."
  - name: "Relation avec les frères et sœurs"
    dice: D6
    count: 6
    description: "Qualité de la relation avec les frères et sœurs"
    entries:
      - id: 1-2
        text: "Relations tendues ou distantes."
        interpretation: "Jalousie, rivalité ou indifférence peuvent expliquer une façon d'éviter les conflits ou de toujours devoir prouver sa valeur."
      - id: 3-4
        text: "Relations normales, avec quelques conflits occasionnels."
        interpretation: "Le personnage sait composer avec les désaccords et faire des compromis, sans laisser les conflits familiaux gouverner toute sa vie."
      - id: 5-6
        text: "Relations très proches et soutenues."
        interpretation: "La loyauté et la protection sont des forces, mais la menace qui pèse sur un proche peut pousser le personnage à agir de manière irrationnelle."
  - name: "Situation économique familiale"
    dice: D6
    count: 6
    description: "Niveau économique de la famille"
    entries:
      - id: 1-3
        text: "Pauvreté, avec des difficultés financières constantes."
        interpretation: "Le personnage a développé une mentalité de survie, de la débrouillardise et une méfiance envers les privilégiés. Il peut vouloir sortir de la misère ou éviter de la reproduire."
      - id: 4-5
        text: "Classe moyenne, suffisamment stable financièrement."
        interpretation: "Une stabilité relative nourrit le désir de la préserver et la peur de la perdre. Une dette, une faillite ou un accident peut la faire basculer."
      - id: 6
        text: "Famille aisée, sans soucis financiers majeurs."
        interpretation: "Le personnage peut bénéficier de privilèges, en ressentir la culpabilité ou être obsédé par le maintien du statut familial. La fortune attire aussi rivaux et obligations."
    custom_rules:
      description: "Ressources optionnelles si utilisé comme règle maison"
      middle_class: "+1D6 x 100 $"
      wealthy: "+2D6 x 100 $"
      notes: "Peut représenter un accès familial, un héritage ou une avance, et non une richesse immédiatement disponible. Peut être remplacé par une dette, une faveur ou un objet ayant une valeur narrative."
  - name: "Influence familiale"
    dice: D6
    count: 6
    description: "Degré d'influence de la famille dans la société"
    entries:
      - id: 1-3
        text: "Aucune influence notable, famille peu connue."
        interpretation: "Le personnage doit se faire reconnaître sans réseau. Il peut chercher à sortir de l'ombre ou être fier de son autonomie."
      - id: 4-5
        text: "Influence modérée, famille bien établie dans une petite communauté."
        interpretation: "La famille est bien connue localement et peut fournir des contacts limités. Ces relations créent des opportunités, mais aussi des obligations."
      - id: 6
        text: "Famille très influente, connue au niveau régional ou sectoriel."
        interpretation: "Le personnage a accès à des informations ou des ressources, en échange d'attentes élevées. Le nom familial attire autant les ennemis que les alliés."
mj_advice:
  - "Un parent, un frère ou une sœur peut demander de l'aide, transmettre une information capitale ou devenir une cible."
  - "Un conflit familial peut mettre le personnage devant un choix entre la mission, la réconciliation et la protection d'un proche."
  - "Une famille pauvre peut être liée à une dette, à un contrat de travail abusif ou à une évacuation impossible."
  - "Une famille aisée ou influente peut être mêlée à un scandale, à une rivalité corporatiste ou à une décision qui menace une colonie."
  - "Une famille disparue ne doit pas automatiquement devenir un mystère central: un objet, un message ou un témoin suffit parfois à faire revenir le passé."
  - "Les résultats doivent fournir des accroches, pas des obligations. Le joueur et le MJ décident ensemble si la famille apparaît réellement en jeu."
---

# ENVIRONNEMENT FAMILIAL

Un arrière-plan familial donne au personnage des attaches, des dettes, des blessures et des responsabilités qui peuvent revenir dans la campagne. Ces tables sont un apport **[CUSTOM]** pour Alien RPG : elles enrichissent l'interprétation et ne remplacent pas les règles officielles.

## UTILISATION

Lors de la création du personnage, lancez 1D6 dans chacune des six catégories ou choisissez les résultats qui correspondent au concept :

1. les parents ;
2. la relation avec les parents ;
3. les frères et sœurs ;
4. la relation avec les frères et sœurs ;
5. la situation économique familiale ;
6. l'influence familiale.

Les résultats n'ont pas besoin d'être uniformément tragiques. Une famille présente peut être une source de soutien et de pression ; une famille absente peut avoir laissé une liberté réelle ou un vide durable. Le joueur peut modifier tout résultat pour préserver l'idée qu'il souhaite jouer.

## CONSEILS D'INTERPRÉTATION

### Les parents

- **Orphelin :** le personnage a appris à se débrouiller seul. Il peut être indépendant et méfiant, ou rechercher des figures parentales de substitution.
- **Un parent vivant :** la perte, l'abandon ou la disparition ont marqué ses relations. Il peut protéger férocement le parent restant, lui en vouloir ou chercher la vérité sur ce qui s'est passé.
- **Deux parents vivants :** une enfance stable peut cacher une pression pour réussir, des attentes contradictoires ou une loyauté familiale difficile à concilier avec la vie du personnage.

### Relations avec les parents

- **Tendues ou distantes :** le personnage porte des non-dits, de la colère ou de l'indifférence. Il peut éviter les confrontations ou les provoquer pour obtenir enfin une réponse.
- **Normales :** l'affection et les désaccords coexistent. Le personnage peut être pragmatique sans idéaliser ni rejeter l'influence parentale.
- **Très proches et soutenues :** la famille apporte confiance et stabilité, mais ses critiques pèsent lourd. Le personnage peut être prêt à prendre des risques pour la rendre fière ou la protéger.

### Frères et sœurs

- **Aucun :** le personnage connaît la solitude ou l'autonomie et peut chercher une famille de substitution parmi les membres du groupe.
- **Un :** le frère ou la sœur peut être un modèle, un rival, une personne à protéger ou un lien encore maintenu par des messages et des dettes.
- **Deux :** la coopération, la compétition et les alliances ont probablement façonné le personnage. La loyauté familiale peut entrer en conflit avec la mission.
- **Trois ou plus :** le personnage a dû occuper une place identifiable : leader, médiateur, oublié, protecteur ou rebelle. Cette place peut se reproduire dans le groupe.

### Relations avec les frères et sœurs

- **Tendues ou distantes :** jalousie, rivalité ou indifférence peuvent expliquer une façon d'éviter les conflits ou de toujours devoir prouver sa valeur.
- **Normales :** le personnage sait composer avec les désaccords et faire des compromis, sans laisser les conflits familiaux gouverner toute sa vie.
- **Très proches et soutenues :** la loyauté et la protection sont des forces, mais la menace qui pèse sur un proche peut pousser le personnage à agir de manière irrationnelle.

### Situation économique familiale

- **Pauvreté :** le personnage a développé une mentalité de survie, de la débrouillardise et une méfiance envers les privilégiés. Il peut vouloir sortir de la misère ou éviter de la reproduire.
- **Classe moyenne :** une stabilité relative nourrit le désir de la préserver et la peur de la perdre. Une dette, une faillite ou un accident peut la faire basculer.
- **Aisée :** le personnage peut bénéficier de privilèges, en ressentir la culpabilité ou être obsédé par le maintien du statut familial. La fortune attire aussi rivaux et obligations.

### Influence familiale

- **Aucune :** le personnage doit se faire reconnaître sans réseau. Il peut chercher à sortir de l'ombre ou être fier de son autonomie.
- **Modérée :** la famille est bien connue localement et peut fournir des contacts limités. Ces relations créent des opportunités, mais aussi des obligations.
- **Très influente :** le personnage a accès à des informations ou des ressources, en échange d'attentes élevées. Le nom familial attire autant les ennemis que les alliés.

## CONSEILS D'INTÉGRATION POUR LE MJ

- Un parent, un frère ou une sœur peut demander de l'aide, transmettre une information capitale ou devenir une cible.
- Un conflit familial peut mettre le personnage devant un choix entre la mission, la réconciliation et la protection d'un proche.
- Une famille pauvre peut être liée à une dette, à un contrat de travail abusif ou à une évacuation impossible.
- Une famille aisée ou influente peut être mêlée à un scandale, à une rivalité corporatiste ou à une décision qui menace une colonie.
- Une famille disparue ne doit pas automatiquement devenir un mystère central : un objet, un message ou un témoin suffit parfois à faire revenir le passé.
- Les résultats doivent fournir des accroches, pas des obligations. Le joueur et le MJ décident ensemble si la famille apparaît réellement en jeu.

## TABLES D'ENVIRONNEMENT FAMILIAL

### Parents et relations parentales

| D6 | Parents | D6 | Relation avec les parents |
|---:|---|---:|---|
| 1 | Orphelin, aucun parent vivant. | 1 | Relations tendues ou distantes. |
| 2-3 | Un parent vivant, l'autre est décédé ou disparu. | 2-4 | Relations normales, avec quelques conflits occasionnels. |
| 4-6 | Deux parents vivants. | 5-6 | Relations très proches et soutenues. |

### Frères et sœurs et relations fraternelles

| D6 | Frères et sœurs | D6 | Relation avec les frères et sœurs |
|---:|---|---:|---|
| 1-2 | Aucun frère ou sœur. | 1-2 | Relations tendues ou distantes. |
| 3-4 | Un frère ou une sœur. | 3-4 | Relations normales, avec quelques conflits occasionnels. |
| 5 | Deux frères et/ou sœurs. | 5-6 | Relations très proches et soutenues. |
| 6 | Trois frères et/ou sœurs ou plus. | | |

### Situation économique et influence familiale

| D6 | Situation économique familiale | D6 | Influence familiale |
|---:|---|---:|---|
| 1-3 | Pauvreté, avec des difficultés financières constantes. | 1-3 | Aucune influence notable, famille peu connue. |
| 4-5 | Classe moyenne, suffisamment stable financièrement. | 4-5 | Influence modérée, famille bien établie dans une petite communauté. |
| 6 | Famille aisée, sans soucis financiers majeurs. | 6 | Famille très influente, connue au niveau régional ou sectoriel. |

## RESSOURCES OPTIONNELLES

Les résultats économiques peuvent donner un avantage de départ uniquement si la table est utilisée comme règle maison. Dans ce cas, marquez clairement le choix **[CUSTOM]** :

- classe moyenne : le personnage gagne **+1D6 x 100 $** ;
- famille aisée : le personnage gagne **+2D6 x 100 $** ;
- aucune ressource supplémentaire pour la pauvreté.

Ces sommes peuvent représenter un accès familial, un héritage ou une avance, et non une richesse immédiatement disponible. Le MJ peut les remplacer par une dette, une faveur ou un objet ayant une valeur narrative.

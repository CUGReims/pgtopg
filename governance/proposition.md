# Processus de contribution et de révision

## Introduction

Avant toute contribution, les contributeurs et la communauté (au sens large) discutent (proposent) les ajouts ou modifications importantes des fonctionnalités.

Ces propositions sont répertoriées dans les tickets, taggés "propositions"/"proposals" dans le dépôt du code de `pgtopg`. 

Ceci afin de démontrer aux contributeurs l'existence de cas concrets d'usage et d'apprécier finement les besoins des utilisateurs, mais aussi afin de fluidifier le processus de contribution. Une visibilité accrue pour les utilisateurs et les responsables sera également ? 

## Types de contribution

Les contributions peuvent être de 4 (quatre) types : 

- **Documentation**
- **Correction de bug** en réponse à un bug ouvert dans les tickets du dépôt.
- **Amélioration significative d'une fonctionnalité existante ou d'un composant**
- **Ajout d'une nouvelle fonctionnalité**

*Note : Les propositions ne sont requises que pour les améliorations ou ajouts de fonctionnalités. Les rapports de bug sont suffisants pour la proposition d'un correctif.*

## Documentation

La documentation peut être modifiée via le process de `pull request`. Toute question liée ou problèmes dans la documentation doit être soumis dans les tickets, suivant en celà le process de tout autre contribution.

## Découverte de bug et processus de correction

Le signalement de bugs et leurs corrections sont gérés dans le dépôt de `pgtopg`.

1. Un utilisateur ou un contributeur soumet un rapport de bug via les tickets (en utilisant le modèle prédéfini),
2. Un contributeur soumet une résolution en ouvrant une demande de mise à jour (pull request) en lien avec le problème (numéro du ticket en description)

## Amélioration significative et nouvelle fonctionnalité

Les améliorations ou nouvelles fonctionnalités sont proposées en ouvrant un ticket de proposition dans le dépôt de `pgtopg`.


This can be initiated in two ways:
- As a community member through an informal discussion. The final feature takes shape through discussions and users feedback.
- As a contributor through an issue using the defined template containing:
   - Concise details of the feature, including its rationale, and use cases supported by user needs
   - Technical explanation of the suggested implementation

*Note: Contributors can still directly open a pull request on the itowns/itowns repository. In this case, it is expected for the pull request to include the same informations as for a proposal issue. PRs submitted without proposal will not likely be prioritized by reviewers.*

Les contributeurs principaux sont chargés de la vérification de l'opportunité et de la validité de la proposition :

- cohérence des process, valeurs et direction du projet
- cohérence technique avec le code existant
- qualité de la solution choisie
- impact sur le reste du code
- non-régression

Un refus de proposition doit être formulé et motivé rationnellement, au besoin en faisant référence aux valeurs du projet, aux process ou aux documents.

Si un contributeur principal a minima exprime un avis défavorable à la proposition, celle-ci peut être maintenue ouverte. La proposition peut être amendée et débattue jusqu'à ce que l'avis défavorable soit levé. Pendant ce laps de temps, aucune implémentation correspondant à la proposition ne doit être faite.

The Product Committee can give advice on proposals, considering existing priorities, resource allocations and knowledge of other features currently planned. The PC can integrate the proposal to its roadmap items, and to the list of items subjects for resource allocations from the Sponsors.

If a consensus is reached, or no negative advice from Core Contributor has been expressed 1 month after the last comment on the proposal, it is considered as acceptable, and a pre-approval of the corresponding Pull Request.

## Implementation & review
## Mise en oeuvre & révision

After the proposal phase, contributors can:
- Implement the feature following the chosen solution
- Open a draft pull request on the main itowns/itowns repository (linking to the proposal issue in `itowns/itowns`)

After implementation, the PR is marked as "Ready", and the review phase can begin : 

1. Functional review: The reviewer ensures that the implementation adds the proposed functionality corresponding to the initial proposal
2. Technical review: The reviewer ensures that the implementation respects the project's processes and meets technical consensus

The review can be made by any contributor. 

Product committee members are also expected to assess the functional aspect of the implementation.

The merge action is achieved by a Core Contributor, who is expected to take responsibility for the code merged, with the collaboration of the initial contributor(s).

This review phase is simplified as previous discussions around the proposal helped understand the author's intentions and choices.

## Sponsors Comittee veto
## Veto du comité de sponsors

**At any point in time, the Sponsors Committee can emit a veto for a proposal or a Pull Request**. This veto must be motivated and its rationale explained in detail, with references to the project's values, processes and global strategy and purpose.



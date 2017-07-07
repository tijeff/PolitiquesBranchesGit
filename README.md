# Politiques de branches Git

Exemple de différentes politiques de gestion des branches Git.

Les sous modules suivants représentent diff&eacute;entes stratégies : 

| Sous module        | Description                                                  |
| ------------------ | ------------------------------------------------------------ |
| **Master**         | Une seule branche                                            |
| **MasterUS**       | Une branche de livraison master & une branche pour chaque US |
| **MasterSprintUS** | une branche de livraison, une par sprint, une par US         | 

## Tickets
| Id      | Type  | Id-Parent | Terminé  |
|:--------|:-----:|:----------|:--------:|
| ID-3214 | US    |         - | &#x2611; |
| ID-3215 | US    |         - | &#x2610; |
| ID-3216 | US    |         - | &#x2610; |
| ID-3217 | Tache | ID-3214   | &#x2611; |
| ID-3218 | Tache | ID-3214   | &#x2611; |
| ID-3219 | Tache | ID-3215   | &#x2611; |
| ID-3220 | Tache | ID-3215   | &#x2610; |
| ID-3221 | Tache | ID-3216   | &#x2610; |
| ID-3222 | Tache | ID-3216   | &#x2611; |

## Sprints
| N° | Id réalisé | US       |
|:---|:-----------|:--------:|
| 1  | ID-3217    | &#x2610; |
| 1  | ID-3219    | &#x2610; |
| 1  | ID-3218    | &#x2610; |
| 1  | ID-3214    | &#x2611; |
| 1  | ID-3222    | &#x2610; |

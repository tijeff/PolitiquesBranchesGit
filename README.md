# Politiques de branches Git

Exemple de différentes politiques de gestion des branches Git.

Les sous modules suivants représentent diff&eacute;entes stratégies : 

| Sous module        | Description                                                  |
| ------------------ | ------------------------------------------------------------ |
| **Master**         | Une seule branche                                            |
| **MasterUS**       | Une branche de livraison master & une branche pour chaque US |
| **MasterSprintUS** | une branche de livraison, une par sprint, une par US         | 

## Tickets
| Id      | Type  | Id-Parent | 
|:--------|:-----:|:----------|
| ID-3214 | US    |         - |
| ID-3215 | US    |         - |
| ID-3216 | US    |         - |
| ID-3217 | Tache | ID-3214   |
| ID-3218 | Tache | ID-3214   |
| ID-3219 | Tache | ID-3215   |
| ID-3220 | Tache | ID-3215   |
| ID-3221 | Tache | ID-3216   |
| ID-3222 | Tache | ID-3216   |

## Sprint
| N° | Id réalisé | US |
|:---|:-----------|:--:|
| 1  | ID-3217    |    |
| 1  | ID-3219    |    |
| 1  | ID-3218    |    |
| 1  | ID-3214    | X  |
| 1  | ID-3219    |    |
| 1  | ID-3222    |    |



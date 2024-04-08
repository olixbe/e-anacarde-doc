# US05 - Valider un nouveau membre

En tant qu'utilisateur ayant les droits nécessaires je souhaite valider un nouveau membre.

## Statut - IN PROGRESS

## Description

Avant de povoir utiliser la plateforme, les nouveaux membres doivent être validés, deux cas possibles :

- Le nouveau membre a rejoint une organisation existante : le gestionnaire de cette organisation valide le compte
- Le nouveau membre a créé une organisation : l'admin de la plateforme valide le compte et attribue un rôle au sein de l'organisation au nouveau membre

## Prérequis

- L'utilisateur est identifié ([US02 - Login](./us-02-login.md))
- Si le nouveau membre a rejoint une organisation : l'utilisateur est gestionnaire de cette organisation
- Si le nouveau membre a créé une nouvelle organisation : l'utilisateur est admin de la plateforme

## Critère d'acceptation

- Le compte du membre est indiqué comme "actif" dans le système et son rôle est correct (gestionnaire ou le rôle attribué par l'admin ou gestionnaire org existante(role "membre"))
- Le nouveau membre peut maintenant se loguer

## Interface utilisateur

TODO

## Web Service

`POST api/administration/user/{id}/validate`

Request Body
```
/
```

Response
```
- HTTP code 200
```

## Modèle de donnée

Voir [page entité-association](../entity-relationship.md)

## Scénario

### Diagramme de séquence
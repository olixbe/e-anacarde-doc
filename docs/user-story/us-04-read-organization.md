# US04 - Consulter le détail des organisations

En tant qu'utilisateur je souhaite consulter le détail d'une ou plusieurs organisations

## Statut - TODO ❌

## Description

Il doit être possible pour un utilisateur ayant le rôle adéquat de consulter le détail :

- d'une (sous-)organisations spécifique
- des utilisateurs liés à une (sous-)organisation
- de toutes les organisations **_( ? à discuter ? )_**

## Prérequis

- L'utilisateur s'est identifié ([US02 - Login](./us-02-login.md))
- L'utilisateur a le rôle adéquat

## Critère d'acceptation

- L'utilisateur ayant les droits peut consulter le détail d'une (sous-)organisation
- L'utilisateur ayant les droits peut consulter les utilisateurs liés à une organisation

## Interface utilisateur

TODO

## Web Service

### GET /api/organization

Request params
```
/
```

Response
```
- HTTP code 200
- Organization list
```

### GET /api/organization/{id}

Request params
```
- Organization id
```

Response
```
- HTTP code 200
- Organization detail
```

### GET /api/organization/{id}/users

Request params
```
- Organization id
```

Response
```
- HTTP code 200
- User list
```

## Modèle de donnée

Voir [page entité-association](../entity-relationship.md)

## Scénario

### Diagramme de séquence
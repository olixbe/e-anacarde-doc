# US02 - Login

En tant qu'utilisateur, je souhaite m'authentifier sur la plateforme.

## Statut - DONE ✔️

## Description

Un utilisateur déjà enregistré et dont le compte est marqué comme validé peut se connecter à la plateforme.

## Prérequis

- L'utilisateur est connu dans le système
- Le compte de l'utilisateur est validé
- L'organisation est validée et active
- L'utilisateur n'est pas encore logué

## Critère d'acceptation

- L'utilisateur peut vérifier qu'il est bien logué sur la plateforme (image de profile, page de configuration du compte, etc.)

## Interface utilisateur

TODO

## Web Service

`POST /api/auth/signin`

Request params
```
- Email
- Password
```

Response
```
- HTTP code 200
- JWT token
```

## Modèle de donnée

## Scénario

### Diagramme de séquence
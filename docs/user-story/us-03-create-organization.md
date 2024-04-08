# US03 - Créer une organisation

En tant qu'utilisateur je souhaite enregistrer une organisation sur la plateforme

## Statut - TODO ❌

## Description

Un utilisateur ayant le rôle adéquat doit pouvoir créer une organisation.

## Prérequis

- L'utilisateur s'est identifié ([US02 - Login](./us-02-login.md))

## Critère d'acceptation

- L'organisation est visible dans le système

## Interface utilisateur

TODO

## Web Service

`POST api/organization`

Request Body
```
- Name
- Address
- Email
- Bank account number
- VAT
- Organization type
```

Response
```
- HTTP code 200
```

## Modèle de donnée

Voir [page entité-association](../entity-relationship.md)

## Scénario

### Diagramme de séquence
# Paperless

## Description

Document management.

## Notes

## Manual setup

1. On the first run, execute `docker compose run --rm paperless createsuperuser`.
2. Move the media folder to a NAS.

## Authentication

### Keycloak setup

Create an OIDC client named `paperless`

Name | Value
---- | -----
Root URL | `https://paperless.yourDomain`
Redirect URIs | `/*`
Authentication flow | Enable: `Standard flow`<br>`Direct access grants`

<!-- ## Notifications

## Logging

## Backup -->

<!-- ## Links

-  -->

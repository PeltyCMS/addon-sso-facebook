# Facebook

Sign in to PeltyCMS with Facebook

Official single sign-on for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Teams that want one-click login with an identity provider customers already use.

## Features

- Client and staff sign-in with **Facebook**
- OAuth / OIDC redirect + session handled by Pelty
- Account linking for existing customers
- Sandboxed WASM SSO provider

## How it works

1. Install **Facebook** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/sso-facebook) inside Pelty Admin → Addons.
2. Open Pelty Admin → Authentication, create a Facebook app, paste client id/secret, and enable the SSO button.
3. Customers hit checkout / login / order flow as usual — Facebook runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working Facebook credentials
- Outbound HTTPS from your panel

## Get it

**[Facebook on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/sso-facebook)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS

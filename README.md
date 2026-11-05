# Facebook

Sign in to PeltyCMS with Facebook

Official **single sign-on** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `sso-facebook`.

## Why this addon

Teams that want one-click login with an identity provider customers already use.

## Features

- Client and staff sign-in with **Facebook**
- OAuth / OIDC redirect + session handled by Pelty
- Account linking for existing customers
- Sandboxed WASM SSO provider

## How it works

1. Install **Facebook** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/sso-facebook) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your Facebook credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use Facebook automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid Facebook API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to Facebook

## Get it

[Facebook on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/sso-facebook)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/sso-facebook
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab

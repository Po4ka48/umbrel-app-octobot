# NikiFlux Community App Store

Community App Store for [umbrelOS](https://umbrel.com).

## Apps

- **OctoBot** (`nikiflux-octobot`) — open-source cryptocurrency trading bot with web UI.

## Install

1. umbrelOS → **App Store** → **Community Stores** → add this repository URL:
   `https://github.com/Po4ka48/umbrel-app-octobot`
2. Install **OctoBot** from the NikiFlux App Store.

## Build

Package layout follows the official [Umbrel Community App Store template](https://github.com/getumbrel/umbrel-community-app-store):

```
umbrel-app-store.yml          # store id + name
nikiflux-octobot/
  umbrel-app.yml              # app listing manifest
  docker-compose.yml          # app_proxy + octobot service
```

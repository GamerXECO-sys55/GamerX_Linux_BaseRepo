# GamerX Linux Repository

This is the official GamerX Linux package repository containing custom packages for the GamerX Linux distribution.

## Repository Structure

- `main/` - Stable packages for production use
- `testing/` - Testing packages for development and testing

## Usage

Add to your `/etc/pacman.conf`:

```ini
# GamerX Linux Testing Repository
[gamerx-testing]
SigLevel = Optional TrustAll
Server = https://gamerxeco-sys55.github.io/GamerX_Linux_BaseRepo/testing

# GamerX Linux Main Repository
[gamerx]
SigLevel = Optional TrustAll
Server = https://gamerxeco-sys55.github.io/GamerX_Linux_BaseRepo/main
```

## Package Count

- Main repository: 90+ packages
- Testing repository: 90+ packages

## Maintainer

GamerX Linux Team

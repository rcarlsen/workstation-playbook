# Workstation configuration

Inspired by (and modified from) the work of several others.

## Workflow
Assumes a clean installation.
It should apply on top of an existing installation, but YMMV.

## Installation
- Create system account
- Sign in with AppleID
- Install Xcode
- Clone configuration repo
- run bootstrap.sh
- ... should install most tools
- manually install Mac App Store apps
  - 1Password
  - Calca
  - LightBlue
- manually install additional apps
  - Charles Proxy
  - PaintCode
- manually install Ghostery Safari extension
- enable FileVault

## Configuration
- Setup selective sync with Dropbox
- Add appropriate vaults to 1Password
- Create / add SSH keys
- Configure GPG / keybase
- Configure editors with FiraCode font and themes
- (may) have to run `rake` in the ~/.vim/ directory to complete janus
  installation.

# Changelog

All notable changes to this deployment definition are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Changed

- Documentation (README, icon source and changelog) rewritten in English.

## [0.0.1]

### Added

- Initial App-as-Code service definition for DDNS Updater, pinned to image `v2.10.0`.
- Web interface on port 8000 with Traefik routing and automatic DNS.
- Persistent data volume and configuration through environment variables.
- README with configuration reference and project icon.

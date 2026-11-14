# Social Network communities Filament

Filament adapter for Communities.

## Installation

composer require liberusoftware/module-social-network-communities-filament

This package is a Liberu Social Network module. Its runtime surface is declared by module.json; presentation adapters depend on the corresponding framework-neutral module.

## License

MIT. See LICENSE.md.

<!-- module-presentation-guide:begin -->
## Presentation architecture and project hosts

- Capability/source key: `liberusoftware/module-social-network-communities`.
- Actual Composer identity: `liberusoftware/module-social-network-communities-filament`.
- [Filament capability plan](https://github.com/liberusoftware/documentation/blob/main/projects/social-network/filament/communities.md) · [Filament standard](https://github.com/liberusoftware/documentation/blob/main/standards/FILAMENT.md) · [Module architecture](https://github.com/liberusoftware/documentation/blob/main/architecture/MODULES.md).

The application owns panel composition, routing, session integration and deployment. This module owns its focused presentation and delegates domain behavior to reviewed public owner contracts. Keep host App aliases, duplicate records and client-only authorization outside reusable package boundaries.

Documented consumer project families:

- [Social Network](https://github.com/liberusoftware/project-social-network-laravel-filament): Profiles, feeds, communities and moderation.

Other web, mobile and desktop presentations are listed in the [project catalog](https://github.com/liberusoftware/documentation/blob/main/projects/REPOSITORIES.md). Those skeletons provide starting structures; links do not establish feature parity, compatible releases or completed device/API integrations. Independent presentation packages keep their own Composer, npm or pub metadata.
<!-- module-presentation-guide:end -->

# PROJECT · Architecture

## Confirmed repository boundaries

- Yo-Fi is a monorepo with a native Android app in `android/` and a future promotional website in `www/` (root README and project instructions).
- Each subproject owns its source, dependency files, local configuration, and build outputs.
- Product requirements and shared project guidance belong at the repository root.

## Pending decisions

Network discovery, identity, data storage, protocols, cryptography, service dependencies, and the first application's internal architecture have not been accepted. See the pending product journey in [PRODUCT](../product/overview.md).

## Documentation reconciliation — 2026-11-23

Confirmed source context, proposals and open decisions are captured in [the active change](../changes/android-journey-discovery/change.md), specifically [PROJECT](../changes/android-journey-discovery/project.md). This root topic remains Pending until approved consolidation.

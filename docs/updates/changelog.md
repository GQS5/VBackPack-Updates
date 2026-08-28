# Changelog

Verified public release history for VBackpack. GitHub Releases remain the
canonical source for downloadable artifacts and full release records.

## 1.0.0

**Released:** August 26, 2026<br>
**Status:** Stable

VBackpack's first stable release introduced the public update-checking system.

### Added

- Credential-free public update manifest support.
- `/backpack update`, with `/vbp update` and `/bp update` aliases.
- Configurable console and permitted-operator notifications.
- Periodic asynchronous checks with bounded retry and backoff.

### Reliability

- Non-blocking requests, request coalescing, and Paper/Folia-safe result delivery.
- Reload- and shutdown-safe scheduling with notification suppression.

### Compatibility

- Java 21 and the historically verified Paper/Folia 1.21.11 paths.
- SQLite remains the default backend and is loaded through Paper's library loader.
- The checker notifies only; it does not download or install releases.

[What's New: 1.0.0](posts/1.0.0.md)

## 0.9.1

**Released:** August 25, 2026

### Improved

- Paper/Folia lifecycle, restart, recovery, Inspector, and bounded multiplayer validation.
- Persistence diagnostics for queue depth, pending saves, retries, and completed writes.
- Structured `VB-XXXXXX` support IDs and read-only Admin Inspector failure handling.
- Achievement presentation and FusionLevel-based visual variants.

### Compatibility

- Existing SQLite/YAML data, UUIDs, PDC keys, permissions, and storage formats remain supported.
- No manual migration or configuration deletion is required.

Verification recorded 874 tests: 873 passed, 0 failed, and 1 skipped.

The canonical artifact record remains in the private source repository.

## 0.9.0

**Released:** August 24, 2026

### Added

- Read-only Admin Inspector for players, Backpacks, storage, Artifacts, Achievements, and recovery state.
- Shared `/backpack` and `/vbp` command routing with diagnostics and structured error IDs.
- Durable, restart-aware Pickup and Magnet recovery handling.

### Improved

- Asynchronous latest-wins persistence for routine gameplay transitions.
- Lightweight administrative summaries and safer Artifact, Fusion, and nested GUI lifecycles.
- SQLite JDBC loading through Paper's library loader instead of the production JAR.

### Fixed

- Paper startup message parsing and a crash-time Pickup/Magnet item-loss window.

Verification recorded 867 tests: 866 passed, 0 failed, and 1 skipped. The earlier `v0.9-dev`
tag is retained as a historical development checkpoint.

The canonical artifact record remains in the private source repository.

## 0.8.3

**Released:** August 22, 2026

### Improved

- Standardized key GUI titles and Achievement presentation.
- Tightened locked Secret Achievement tooltips.
- Kept BackpackMenu controls consistent across supported page sizes.

### Fixed

- Restored the Achievements button on smaller BackpackMenu layouts.

Verification recorded 793 tests: 792 passed, 0 failed, and 1 opt-in benchmark skipped.

The canonical artifact record remains in the private source repository.

## 0.8.2

**Released:** August 22, 2026

### Fixed

- Creative Backpack placement now transfers the held UUID-backed Backpack into the placed block.
- Native head placement behavior remains authoritative for orientation, support, consumption, and rollback.

### Changed

- Public plugin identity and presentation were updated to VBackpack by VackStudio.
- Existing installations receive the documented one-time data-folder migration without changing
  UUIDs, PDC keys, permissions, or storage formats.

The canonical artifact record remains in the private source repository.

## 0.8.1

**Released:** August 21, 2026

- Renamed the public release artifact and presentation branding to VBackpack by VackStudio.
- Preserved internal identifiers, data folders, permissions, PDC namespaces, and API/package names.

The canonical artifact record remains in the private source repository.

## 0.8.0

**Released:** August 21, 2026

### Added

- Native V1 Backpack, Artifact, Fusion, and Journal GUI presentation.
- Achievements V1 with Progression, Mastery, and Secret categories.

### Improved

- Navigation, tooltips, Artifact identity, recovery delivery, persistence, and GUI session handling.

### Fixed

- Artifact fusion presentation, floor-head rotation, and stale or duplicate state updates.

The canonical artifact record remains in the private source repository.

## 0.7.1

**Released:** August 18, 2026<br>
**Status:** Private security hotfix

The surviving history records fixes for placed/portable authority transitions, GUI session
authorization, duplicate opens, protected placed Backpacks, migration preservation, and stale
scheduled mutations. This was a private release, not a public customer milestone.

The canonical artifact record remains in the private source repository.

## 0.7.0

**Released:** August 17, 2026<br>
**Status:** Private release

The surviving history records tier-based Artifact slot progression, operator diagnostics, release
metadata checks, configuration validation, and Artifact storage and acquisition hardening. This
was a private development and controlled-QA release, not the public paid `1.0.0` milestone.

The canonical artifact record remains in the private source repository.

## 0.6.6

**Released:** August 15, 2026

Production hardening for revision-aware saves, delete fencing, session lifecycle, migration safety,
Soulbound recovery, Artifact mutation validation, and safer Fusion previews.

The canonical artifact record remains in the private source repository.

## 0.6.5

**Released:** August 9, 2026

Completed the public identity transition to VBackpack by VackStudio while preserving storage,
configuration, and public API compatibility.

The canonical artifact record remains in the private source repository.

## 0.6.4

**Released:** August 8, 2026

### Fusion

- Introduced FusionLevel as separate progression from permanent Artifact rarity.
- Added fusion-aware textures, GUI displays, lore, behavior scaling, persistence, and validation.
- Preserved compatibility with existing Artifact data and legacy items.

The local consolidated changelog does not contain this release; these details are taken from the
canonical remote GitHub Release and its published artifact.

The canonical artifact record remains in the private source repository.

## 0.6.3

**Released:** August 8, 2026

Activated survival Artifact behaviors including Magnet, Compactor, Smelting, Soulbound, Swift, and
Experience, with the Artifact inventory listener and Backpack give command.

The canonical artifact record remains in the private source repository.

## 0.6.2

**Released:** August 8, 2026

Added custom head textures for Backpack tiers, Artifacts, and GUI buttons, with corresponding
configuration and regression coverage.

The canonical artifact record remains in the private source repository.

## 0.6.1

**Released:** August 8, 2026

Introduced the runtime Artifact behavior layer and activated Artifact behavior handling in gameplay.

The canonical artifact record remains in the private source repository.

## 0.6.0

**Released:** August 8, 2026

Added tiered multi-page Backpacks, tier-based capacity, navigation, upgrade handling, and related
storage and persistence coverage.

The canonical artifact record remains in the private source repository.

## 0.5.4

**Released:** August 7, 2026

Stability and data-integrity hardening for persistence, storage, configuration, and Backpack state.

The canonical artifact record remains in the private source repository.

## 0.5.3

**Released:** August 6, 2026

Added Artifact acquisition through admin commands, boss drops, chest loot, and the existing Artifact,
Fusion, and GUI systems.

The canonical artifact record remains in the private source repository.

## 0.5.2

**Released:** August 6, 2026

Security and stability update addressing the verified high-severity findings recorded in the release
history.

The canonical artifact record remains in the private source repository.

## 0.5.1

**Released:** August 6, 2026

Polished the Swift Artifact behavior, item presentation, and the related public behavior contract.

The canonical artifact record remains in the private source repository.

## 0.5.0

**Released:** August 5, 2026

Introduced the Artifact system, Artifact storage and slots, management GUI, behavior contracts, and
three-identical-input Fusion progression.

The canonical artifact record remains in the private source repository.

## 0.3.0

**Released:** August 4, 2026

Foundation release covering architecture, storage backends, migration, API behavior, events,
ownership serialization, and configuration validation.

The canonical artifact record remains in the private source repository.

## 0.2.3

**Released:** August 4, 2026

Critical reliability fixes for configuration validation, Backpack management, inventory protection,
and release quality.

The canonical artifact record remains in the private source repository.

## 0.2.2

**Released:** August 4, 2026

Platform compatibility and reliability improvements, including platform detection and compatibility
documentation.

The canonical artifact record remains in the private source repository.

## 0.1.0

**Released:** August 3, 2026

Initial public release.

The canonical artifact record remains in the private source repository.

## Development Checkpoints

### v0.9-dev

**Recorded:** August 24, 2026<br>
**Status:** Pre-release / development checkpoint

This source checkpoint preceded the official `v0.9.0` release and is not part of the stable
release stream.

The canonical source checkpoint remains in the private source repository.

[← What's New](index.md) · [Back to Home →](../index.md)

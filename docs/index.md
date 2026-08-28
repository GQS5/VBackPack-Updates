<!-- markdownlint-disable MD033 -->

# VBackpack

## More than storage. A complete backpack experience.

VBackpack is a commercial Minecraft backpack, storage, and progression plugin
by **VackStudio**. It gives portable storage a persistent identity and layers
backpack progression, Artifacts, Fusion, Achievements, and read-only tools for
server administrators on top.

<div class="vp-cards" markdown>

<a class="vp-card" href="getting-started/">
<strong>Get started</strong>
<span>Take a new server from installation to a first backpack session.</span>
</a>

<a class="vp-card" href="installation/">
<strong>Installation</strong>
<span>Review Java, Paper, Folia, and first-start requirements.</span>
</a>

<a class="vp-card" href="backpacks/">
<strong>Backpacks</strong>
<span>Understand persistent identity and progression-focused storage.</span>
</a>

<a class="vp-card" href="artifacts/">
<strong>Artifacts</strong>
<span>Explore the approved Artifact lineup and progression concepts.</span>
</a>

<a class="vp-card" href="commands/">
<strong>Commands</strong>
<span>Find player and administrator command references.</span>
</a>

<a class="vp-card" href="admin-inspector/">
<strong>Admin Inspector</strong>
<span>Investigate player storage without changing it.</span>
</a>

</div>

## Core Systems

### Backpack progression

Backpacks are individual, persistent storage objects. Multiple backpack types
make capacity and ownership part of the gameplay journey rather than a set of
interchangeable command inventories.

### Portable persistent storage

Backpack contents and state are persisted with SQLite. No external database
server is required, and Paper loads the SQLite JDBC library automatically.

### Artifacts and Fusion

Artifacts enhance a backpack beyond raw storage. Fusion provides an in-game
path for Artifact progression; current balance and interface details belong to
the installed release.

### Achievements

Discoverable goals give players another way to progress. Some discoveries are
intentionally secret and are not revealed in the public documentation.

### Administrative inspection

The read-only Admin Inspector provides paginated views of players, backpacks,
contents, Artifacts, and Achievement progress. It is designed for support and
investigation without taking control of player storage.

## Compatibility Baseline

| Component | Baseline |
|---|---|
| Java | 21 |
| Paper | 1.21.11 |
| Folia | 1.21.11 where publicly supported |

See [Compatibility](compatibility.md) before installing. VBackpack source
code and customer downloads are not hosted on this site.

## Public Updates

The update checker reads the repository's [stable metadata](https://github.com/GQS5/VBackPack-Updates/blob/main/stable.json).
Customer downloads and release announcements are distributed through the
official marketplace resource, not this documentation repository.

<div class="vp-attribution">

Documentation for VBackpack by **VackStudio**.

</div>

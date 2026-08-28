# Installation

## Requirements

- Java 21
- Paper 1.21.11
- Folia 1.21.11

VBackpack does not require a separate external plugin dependency. SQLite is the
storage engine, and its JDBC library is loaded through Paper's library loading
mechanism. Do not manually install `sqlite-jdbc` as another plugin.

## Install VBackpack

1. Stop the server and take a maintenance window for the change.
2. Download the customer JAR from the official marketplace resource.
3. Place the VBackpack JAR in the server's `plugins/` directory.
4. Start the server.
5. Review the startup log and confirm that VBackpack enabled without an error.

On first startup, Paper may need network access to resolve the declared SQLite
library. This is normal; allow the resolution to complete. Do not use a source,
thin, or development artifact as the server plugin.

## Updates and Restarts

Stop the server before replacing a plugin JAR. Keep a backup of the server and
plugin data, install one release at a time, and perform a clean restart after
an update. Do not delete storage files as a first troubleshooting step; see
[Storage](storage.md) and [Troubleshooting](troubleshooting.md).

[← Documentation Home](index.md) · [Next: Backpacks →](backpacks.md)

# Storage

VBackpack uses SQLite-backed persistence for backpack contents and state. No
external database server is required.

The SQLite JDBC library is loaded automatically through Paper's library loading
mechanism. Server owners do not need to install `sqlite-jdbc` manually or add a
separate dependency plugin.

Backpack data is designed for durable persistence and safe server restart
handling. Stop the server before copying or backing up plugin data, and keep
backups outside the live data directory.

Do not delete the plugin database or data files as a first recovery step. If a
startup or persistence problem occurs, preserve the files and follow
[Troubleshooting](troubleshooting.md) so useful diagnostics remain available.

[← Documentation Home](index.md) · [Next: Compatibility →](compatibility.md)

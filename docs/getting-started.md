# Getting Started

This short path gets a new player from installation to their first backpack
session.

## 1. Install VBackpack

Follow the [installation guide](installation.md) and confirm the server meets
the [compatibility requirements](compatibility.md).

## 2. Start the Server

Start the server normally and review the startup log for plugin errors. If the
first start needs to download the SQLite library, allow the server network
request to complete before diagnosing the installation.

## 3. Verify the Plugin

As an operator, run:

```text
/backpack info
```

`/vbp info` and `/bp info` are established aliases. If the command is not
available, see [Troubleshooting](troubleshooting.md).

## 4. Check Permissions

Players need the permissions granted by your server's normal permission setup.
See the [permission reference](permissions.md). Operators can use the confirmed
admin permission for inspection:

```text
vbackpack.admin.inspect
```

## 5. Obtain and Open a Backpack

Obtain a backpack through the server's configured gameplay path or an
administrator. Operators can use the verified administrative command described
in [Commands](commands.md). Open the backpack through its in-game interaction,
then store an item and close it normally.

## 6. Explore Progression

Once the storage loop is familiar, explore [Artifacts](artifacts.md),
[Fusion](fusion.md), and [Achievements](achievements.md). Exact balance,
recipes, and tier values are release or configuration dependent and should be
read from the current in-game interface rather than assumed from this guide.

## 7. Next Steps

Server owners should review [Storage](storage.md), [Configuration](configuration.md),
and [Troubleshooting](troubleshooting.md). Administrators can learn the
[read-only Inspector](admin-inspector.md).

[← Documentation Home](index.md) · [Next: Installation →](installation.md)

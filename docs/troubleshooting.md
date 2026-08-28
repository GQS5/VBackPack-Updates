# Troubleshooting

## The Plugin Does Not Load

Confirm that the server is running Java 21, the JAR is in `plugins/`, and the
server platform and version match [Compatibility](compatibility.md). Read the
first VBackpack-related error in the startup log rather than only the final
summary.

## Wrong Java or Server Version

Check `java -version` and the server version. Upgrade to Java 21 and Paper or
Folia 1.21.11 before investigating gameplay behavior.

## Library or Network Failure

On first startup, Paper may need network access to load the SQLite JDBC library.
Check the server's network, DNS, firewall, and proxy rules, then restart after
the dependency can resolve. Do not manually install the JDBC library as a
plugin.

## Backpack GUI Issue

Confirm the player is using a current customer release and test with a clean
server configuration when possible. Record the exact action, player context,
server platform, Java version, and relevant log lines.

## Persistence or Startup Issue

Do not delete databases or plugin data. Stop the server, preserve a backup of
the affected files, and collect the startup log and any diagnostics available
to an operator. A clean restart should be performed only after the backup is
secured.

## Reporting a Problem

Use the official support destination associated with the marketplace resource
when it is available. Include the VBackpack version, Java version, Paper/Folia
version, reproduction steps, relevant logs, and whether the issue survives a
clean restart. Remove credentials, private IPs, and unrelated server data.

[← Documentation Home](index.md) · [Next: FAQ →](faq.md)

# CoCut releases

Downloads and auto-update files for CoCut. Get the latest version from
[Releases](../../releases/latest).

CoCut checks `releases/latest/download/latest.json` on start. Every update file is signed with
the CoCut updater key (minisign / ed25519), and the app refuses any file whose signature doesn't
match.

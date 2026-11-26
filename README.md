# Mod Catalog

Personal, non-commercial project that catalogs Minecraft mods I find on YouTube,
to help me maintain a small private modpack for me and a friend.

## What it does
- Reads public project metadata (name, summary, supported game versions,
  mod loaders, dependencies) from Modrinth and, if approved, the CurseForge API.
- Builds an Excel spreadsheet filtered to Minecraft 1.20.1 / 1.21.1
  on Forge / NeoForge.
- Every entry links back to the official project page.

## What it does NOT do
- It does not download, host, mirror or redistribute any mod files.
- All downloads happen on the official CurseForge / Modrinth pages.
- No ads, no subscriptions, no monetization.

## API usage
A one-time batch of a few thousand metadata requests, followed by
occasional small updates. Requests are rate-limited and cached locally.

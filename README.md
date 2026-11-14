# VESPERA V6.3 — Fusion Glass

A combined build that keeps the V6.2 application structure and features while bringing the V4 visual language forward.

## What is combined
- V4-inspired visual treatment: calmer charcoal background, restrained blue/pink accent lighting, elegant glass panels, softer controls and clearer spacing.
- V6.2 feature set and application logic: daily tasks and task catalog, rank/XP progression, fitness profile and activity logs, local assistant task organization, notifications, Arabic/English, six accent themes, backup import/export, and offline PWA shell.
- Shape hierarchy: circular player rank and progress indicators; circular metric orbs; rectangular glass surfaces for tasks, activity, assistant and settings; compact rounded controls; floating navigation dock.

## Compatibility and privacy
- Keeps the V6.2 local storage key (`vespera_v5_data`) so existing V6.2 browser data remains available on the same origin.
- No login, cloud AI, remote AI API, Worker, CDN, or external runtime library is added.
- Data remains in the browser's local storage. Export a backup before clearing browser data or changing devices.
- Browser notifications depend on HTTPS, browser support and user permission.

## Deploy
Upload all five files in this ZIP directly to the root of a static HTTPS host or the repository root used for the V6.2 deployment. The service worker cache name has been updated for V6.3.

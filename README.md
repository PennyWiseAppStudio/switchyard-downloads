# Switchyard downloads

Windows installers for [Switchyard](https://switchyard-web-amber.vercel.app), a
desktop Git client by Pennywise App Studio.

This repository holds **releases only** — there is no source here. The
application and the website are developed privately; this exists so the
installer has a public home, because a private repository's release assets are
not reachable without signing in.

## Getting the app

The download button on the site points at the newest release. It resolves
through a name that does not change with the version:

    /releases/latest/download/Switchyard-Setup.exe

Each release also carries the versioned file, so a particular build stays
identifiable after the fact.

## Upgrading from 0.1.8 or earlier

Version 0.1.9 installs under a new application ID, so Windows treats it as a
separate program rather than an update. **Uninstall the old Switchyard first**
(Settings → Apps → Installed apps), then run the new installer. Your open
repositories, panel sizes and theme are kept: they are stored by the app's
name, which has not changed.

## Help

How to use the app, with every keyboard shortcut:
<https://switchyard-web-amber.vercel.app/docs/> — or press **F1** in the app.

Problems: <pennywise.appstudio@gmail.com>

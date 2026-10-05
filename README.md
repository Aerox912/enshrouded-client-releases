# Enshrouded client launcher downloads

Binary downloads for the privately maintained Normal and Cheeze launchers.

Normal matches the Soulrend profile. Cheeze adds the six extra XHL mods for the Enshrouded profile. Both enable the five selected EMBER storage, buff and building features, with Flame Altar requirements preserved. Global XP Share belongs to the server packages and is never installed on clients.

Download your channel's ZIP from [Releases](https://github.com/Aerox912/enshrouded-client-releases/releases). Extract it and run `Enshrouded-Mods.exe`. The download is below 10 MB and requires no GitHub login. Required dependencies download on demand; restricted original mods must be obtained from their authors and imported using **Settings → Import original ZIP**.

After the first run, the stable launcher is `%LOCALAPPDATA%\EnshroudedClientMods\Enshrouded-Launcher.exe`. Settings controls the channel and automatic updates. Updates download at startup and every six hours while running, then apply when the game is closed and the launcher is idle. Close the previous launcher through its tray menu before the initial migration from Normal 3.9 or Cheeze 1.0.2.

The signed files under `channels/` identify complete published releases. Launcher packages and executables are checked by SHA-256; the public RSA verification key is in `update-public.xml`. A failed build or publication does not promote a channel. Keep recovery backups if an update reports an error.

Credits, original download links, compatibility and profile manifests: [enshrouded-mod-patches](https://github.com/Aerox912/enshrouded-mod-patches). Maintained minimap and camera code retain their upstream licenses and credits. The installer application is for private use; its source is not distributed here. This repository contains no original restricted mods, game executables, game resource containers, worlds or personal settings.

Server packages are published separately in [enshrouded-server-compat](https://github.com/Aerox912/enshrouded-server-compat/releases). The migration does not deploy to live servers or automatically publish on Nexus.

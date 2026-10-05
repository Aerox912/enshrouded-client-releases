# Enshrouded Mod Manager

One app with **Normal** and **Cheeze** profiles. All 12 mods are visible in two rows. Hover over a mod to learn what it does, or use its Nexus badge to visit the original author's page. Key bindings are centralized under **Settings > Hotkeys**.

[Download the latest release](https://github.com/Aerox912/enshrouded-client-releases/releases/latest). The ZIP contains both **Enshrouded-Setup.exe** for a per-user installation and **Enshrouded-Mods.exe** for portable use. The ZIP stays below 15 MB and requires no GitHub login. Both profiles' Nexus originals and maintained patches are bundled; larger public dependencies download automatically without signing in. Both options use the same settings and updater.

Select Normal or Cheeze in the app to apply that profile's defaults with the game closed. You can also choose individual mods and apply a custom selection. Switching profiles keeps the same application and preserves hotkeys, minimap options, camera preferences, OptiScaler settings and the original uninstall baseline.

Normal includes the minimap, first-person camera, Electric Blink, Hoarder's Helper, OptiScaler and the selected EMBER features. Cheeze adds Vein Mining, Auto Loot, Max Stack, Unlimited Gifting Range, Rested Enhanced and Grappling Hook Pull 2x. Both profiles enable EMBER magic furniture, magic production stations, buff refresh, no-build-zone removal and building in Shroud fog, with Flame Altar requirements preserved. Global XP Share belongs to the separate server packages and is never installed on clients.

There are no manual Nexus downloads or original archive imports. OptiScaler, EML, Shroudtopia and the maintained minimap download automatically from pinned public releases. Visual C++ is downloaded only when needed. Verified files are cached and reused, allowing installation and profile switching offline once the required dependencies are available. Dependency downloads, especially the graphics libraries, are larger than the manager ZIP. Game-data patches are generated against the recipient's matching game installation.

Use **Check for updates** on the home screen, in Settings or in the tray menu. Automatic checks run at startup and every six hours; disable them in Settings if preferred. Installation waits until Enshrouded is closed and the manager is idle. The tray icon is blue for Normal and gold for Cheeze.

Previous 4.x editions receive the small 4.2.1 compatibility update first, then the new manager through the bundled-release feeds. Users of Normal 3.9 or Cheeze 1.0.2 should close the old launcher through its tray menu and download this manager once. The stable launcher entry point is `%LOCALAPPDATA%\EnshroudedClientMods\Enshrouded-Launcher.exe`. A Setup installation also provides a Start menu shortcut.

Signed metadata and SHA-256 checksums verify every app update. The `bundled-channels` feeds identify the same manager release. The legacy `channels` feeds retain 4.2.1 so launchers with the old size limit can migrate safely. Failed builds or publication leave the previous feeds active. Previous app versions and recovery backups are retained.

Original author credits, download links, compatibility and profile manifests: [enshrouded-mod-patches](https://github.com/Aerox912/enshrouded-mod-patches). Maintained minimap and camera code retain their upstream licenses and credits. Installer source is private. Third-party originals retain their authors' rights and notices. This bundle does not grant further redistribution rights. No game executables, game resource containers, worlds or personal settings are included.

[Server packages](https://github.com/Aerox912/enshrouded-server-compat/releases) are published separately. These pipelines do not deploy to live servers or automatically publish on Nexus.

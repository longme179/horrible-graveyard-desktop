# Symlinks (followed, kept or excluded)

Generated: 2026-10-31 18:05:26 UTC

## Followed - content fetched from the link target into the repo
- .config/quickshell/lme-shell -> /home/kimhoanglong/lme-fedora-niri-qs (dir link, 702 file(s), 25 MiB)
- .local/bin/app-manager -> /home/kimhoanglong/Applications/AppManager (file link, 1 file(s), 41 MiB)
- .local/bin/zed -> /home/kimhoanglong/.local/zed.app/bin/zed (file link, 1 file(s), 2 MiB)

## Kept as symlinks (target already inside the backup or not followable)
- .config/gtk-4.0/assets -> /usr/share/themes/adw-gtk3-dark/gtk-4.0/assets [dangling: target does not exist (link kept)]
- .config/gtk-4.0/gtk.css -> /usr/share/themes/adw-gtk3-dark/gtk-4.0/gtk.css [dangling: target does not exist (link kept)]
- .config/gtk-4.0/gtk-dark.css -> /usr/share/themes/adw-gtk3-dark/gtk-4.0/gtk-dark.css [dangling: target does not exist (link kept)]
- .config/rofi/themes/meloworld-tokens.rasi -> /home/longme/.config/rofi/themes/meloworld-tokens-dark.rasi [dangling: target does not exist (link kept)]

Links whose target is deny-listed are listed in EXCLUDED.md with a
deny-target rule. rice-restore.sh --relink recreates followed links.

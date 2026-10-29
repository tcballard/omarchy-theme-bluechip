# Architecture

`colors.toml` is the flat semantic palette. Omarchy renders its own application templates on selection. `icons.theme` selects Yaru-blue; `chromium.theme` supplies the intended navy browser tint. No custom executable Lua or startup hooks are shipped.

`backgrounds/` contains ten 8192 × 5120 WebP wallpapers. `backgrounds/intros/` contains the matching eagle entrance for native Omarchy intro support; `optional/` contains the 16:9 aviation wallpaper outside the default rotation. Alphabetic ordering selects the monochrome pressed-metal composition first. Editable logo compositions live under `docs/design-sources/`.

Authoring scripts, tests and docs are excluded from Git archives by export-ignore. Direct Git-based Omarchy installation may stage documentation, but no authoring code is invoked by the theme. Never edit generated current-theme files as the source of truth.

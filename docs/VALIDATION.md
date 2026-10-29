# Validation — 28 October 2026

Target: Omarchy Quattro 4.0.0.alpha, upstream commit b79c846e364aa71c708d7671afa9fb07026cde5e.

Passed:
- Bundled Omarchy theme skill checker: palette structure, required files and contrast checks.
- Foreground/background contrast 13.06:1; foreground/selection 7.31:1; accent/background 7.00:1.
- Actual upstream headless theme staging and GNU Awk template rendering in an isolated temporary HOME.
- All 20 expected stock template outputs exist without unresolved template tokens; generated TOML and JSON parse successfully.
- Local-source and Git-installed staging produce matching application configurations.
- First background selection resolves to monochrome pressed metal.
- All ten WebP images decode and have exact 16:10 aspect ratios.
- Official logo path geometry was retained in the monochrome SVG revision; rendered image visually reviewed.
- Installer and restore script Bash syntax checks.

Not run:
- A live Omarchy/Hyprland session or XPS display test.
- Actual non-root installer/restore execution: this environment cannot change UID. Headless upstream tests use a disposable home and do not constitute a live installation.
- Per-application runtime rendering, icons, browser policy, GTK appearance, Lua execution, hardware keyboard colour or registry review.

The package uses the system's own templates rather than shipping generated app configurations. Compatibility can vary as Quattro evolves. No public release or registry submission has been made.

## 8K wallpaper update (29 October 2026)

All eleven WebP dimensions and SHA-256 hashes match the delivered export manifest. Ten theme WebP files are 8192 × 5120; the optional photo is 8192 × 4608. The MP4 basename matches the eagle WebP under backgrounds/intros. The upstream intro resolver was checked on this date. This does not establish live XPS playback or crop acceptance.

`./tests/run` passed: project structure, identity, README links and CI policy, plus all five portable tests.

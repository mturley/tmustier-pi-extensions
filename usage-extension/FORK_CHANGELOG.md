# Fork Changelog

Releases of `@mturley/pi-usage-extension`. Upstream release notes live in [CHANGELOG.md](CHANGELOG.md).

## [0.10.4] - 2026-10-26

### Upstream baseline
- Rebased on upstream `@tmustier/pi-usage-extension` 0.10.0.

### Fork-specific
- Preserve the fork's independent Today and This Month Powerline statuses, with dimmed labels.

## [0.10.3] - 2026-10-20

### Upstream baseline
- Based on upstream `@tmustier/pi-usage-extension` 0.9.5.

### Fork-specific
- Publish Today and This Month totals under separate status keys so Powerline can render them as independent items.
- Dim the `Today:` and `This Month:` labels while keeping the amounts at normal intensity.

## [0.10.2] - 2026-10-09

### Upstream baseline
- Based on upstream `@tmustier/pi-usage-extension` 0.9.5.

### Fork-specific
- Add live Today and This Month usage totals to the Pi statusline, refreshed at session start and after each agent run.

## [0.10.1] - 2026-10-08

### Upstream baseline
- Based on upstream `@tmustier/pi-usage-extension` 0.9.5.

### Fork-specific
- Document fork attribution in the project and usage-extension READMEs; update install instructions and package metadata for `@mturley/pi-usage-extension`.

## [0.10.0] - 2026-10-08

### Upstream baseline
- Based on upstream `@tmustier/pi-usage-extension` 0.9.5.

### Fork-specific
- Add the **This Month** period, from local midnight on the first day of the month, to the usage dashboard.
- Publish the standalone package as `@mturley/pi-usage-extension`.

# Blue Metal Dark Theme

![versie](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FLeonCB%2Fblue_metal_dark%2Freleases%2Flatest&query=%24.tag_name&label=versie&color=blue)
[![Validate](https://github.com/LeonCB/blue_metal_dark/actions/workflows/validate.yml/badge.svg)](https://github.com/LeonCB/blue_metal_dark/actions/workflows/validate.yml)

Dark theme for Home Assistant, heavily inspired by the Blue Night Theme by ksya.

## Installation

### HACS
1. Make sure `frontend: themes: !include_dir_merge_named themes` is in your `configuration.yaml`.
2. HACS → three-dot menu → **Custom repositories** → add `https://github.com/LeonCB/blue_metal_dark` with category **Theme**.
3. Install **Blue Metal Dark Theme**, then run the `frontend.reload_themes` action (or restart Home Assistant).
4. Pick **Blue Metal Dark** under your profile → Theme.

### Manual
Copy `themes/blue_metal_dark.yaml` to `config/themes/blue_metal_dark/` and reload themes.

## Requirements

The theme uses UIX (available via HACS) for some card styling (`uix-theme`, `uix-card-yaml`). Without UIX the colors still work; only those extra tweaks are skipped.

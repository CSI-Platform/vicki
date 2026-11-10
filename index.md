# vicki wiki

A public demo of the LLM Wiki pattern: raw captures are compiled into interlinked markdown pages, and the route map makes the links visible.

## Wiki

- [Hulk inventory](wiki/hulk-inventory.md) — machine and software summary from the AppLens scan
- [Hulk USB and wireless connections](wiki/hulk-connections.md) — USB, Wi-Fi, Bluetooth, serial, and network settings

## Raw

- [AppLens inventory JSON](raw/AppLens_Results_hulk_2026-11-08T175336Z.json) — sanitized machine and software scan, 2026-11-08
- [USB, Wi-Fi, Bluetooth, and serial capture](raw/hulk-usb-connections-2026-11-09.txt) — sanitized live capture, 2026-11-09

## Placeholders

- `notes/` — private in the source wiki; not included here
- `experiments/` — empty in the source wiki; kept as a route placeholder

## Route map

- [`index.html`](index.html) — interactive route map of the pages, sources, and sections
- [`wiki/hulk-connections-map.svg`](wiki/hulk-connections-map.svg) — static connection diagram

# vicki

A small public demo of an LLM-compiled wiki, rendered as an interactive route map.

**Open [`index.html`](index.html) in a browser.** No build step, no dependencies.

The demo data comes from a Linux workstation called Hulk. The wiki has two compiled pages, two raw captures, and a static connection diagram. The route map is the interface: it shows pages, sources, sections, and the links between them.

## Use the map

- Hover a node for about one second to open its route card.
- Move away early and the dwell cancels.
- Click a node to pin its card.
- `Esc`, the close button, or clicking outside dismisses it.
- Deep links work: `index.html#wifi`, `index.html#esp32`, `index.html#serial`.

## Layout

```text
index.html                  interactive route map
index.md                    content-oriented wiki index
SCHEMA.md                   schema for the wiki
AGENTS.md                   local path map for the HULK catalog
wiki/                       compiled pages and the static diagram
raw/                        sanitized immutable captures
notes/                      placeholder for private notes
experiments/                placeholder for experiment work
```

## The wiki pattern

This follows Andrej Karpathy's [LLM Wiki](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) idea:

- `raw/` is the source of truth and stays immutable.
- `wiki/` is the compiled, interlinked layer.
- `SCHEMA.md` is the schema that keeps the structure consistent.
- `index.md` catalogs pages; the route map makes the links visible.

## Privacy

This is the public copy. Host and user names, local IP addresses, MAC addresses, SSIDs, and device paths were replaced with documentation values. The raw captures in `raw/` are sanitized. No private notes, secrets, weights, or environments are included.

## Credits

See [CREDITS.md](CREDITS.md). The design pass follows the [unslop](https://github.com/heydamir/unslop) method by Damir Sokolovsky, licensed CC BY 4.0.

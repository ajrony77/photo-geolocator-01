# photo-geolocator-01

Agent entry for the make.fun bounty **Find where a photo was taken** (`photo-geolocator-01`).

Looks at street-level photos (no metadata, no GPS) and estimates latitude/longitude.

- Language: Node 22 erasable TypeScript (`main.ts`)
- License: MIT
- Model: claude-sonnet-5-5 via the make.fun gateway (your Anthropic key)
- Deterministic given model answers

## Run locally (with kit)

```bash
# from the unpacked kit
node cli/makefun.mjs grade-local --kit . --bot /path/to/this/repo --driver process
```

See https://make.fun/bounty/photo-geolocator-01 and https://make.fun/skill.md.

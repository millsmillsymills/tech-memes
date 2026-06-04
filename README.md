# tech-memes

Personal stash of tech/cyber memes.

## Index

| File | Preview |
|------|---------|
| `claude-my-bro.jpg` | ![](memes/claude-my-bro.jpg) |
| `cyber-bully.png` | ![](memes/cyber-bully.png) |
| `cyber-dystopia.jpg` | ![](memes/cyber-dystopia.jpg) |
| `cyber-panel.jpg` | ![](memes/cyber-panel.jpg) |
| `eee-wroom-dab.jpg` | ![](memes/eee-wroom-dab.jpg) |
| `hac.jpg` | ![](memes/hac.jpg) |
| `hacker-knows-my-address.jpg` | ![](memes/hacker-knows-my-address.jpg) |
| `hackers-address.jpg` | ![](memes/hackers-address.jpg) |
| `linux.jpg` | ![](memes/linux.jpg) |
| `lose-access.jpg` | ![](memes/lose-access.jpg) |
| `me-irl.jpg` | ![](memes/me-irl.jpg) |
| `moon.jpg` | ![](memes/moon.jpg) |
| `secops.jpg` | ![](memes/secops.jpg) |
| `vpn-tunneling.png` | ![](memes/vpn-tunneling.png) |
| `weekend.jpg` | ![](memes/weekend.jpg) |
| `worst-code.jpg` | ![](memes/worst-code.jpg) |

## Manifest

`memes.json` is the machine-readable index — `{ id, file, alt }` per meme. It's
the source of truth for the millsymills.com memes gallery, which generates its
data from this file (see that repo's `scripts/sync-memes.mjs`). `id` is stable
(don't rename), `file` is the bare filename under `memes/`, `alt` is
accessibility text.

## Add a meme

1. Drop image in `memes/` (lowercase ext: `.jpg` / `.png` / `.gif`).
2. Add a row to the table above **and** an entry to `memes.json`
   (`{ id, file, alt }` — unique stable `id`, real `alt` text).
3. Commit, push.

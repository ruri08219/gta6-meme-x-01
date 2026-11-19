# GTA 6 Meme — "Waited 13 Years, Fell Asleep During the Download"

Entry for the [gta6-meme-x-01 bounty](https://make.fun/bounty/gta6-meme-x-01) on
[make.fun](https://make.fun): post a GTA 6 meme on X. Top 50 entries share $500.

![competition](https://img.shields.io/badge/competition-gta6--meme--x--01-magenta)
![reward](https://img.shields.io/badge/reward-%24500-brightgreen)
![status](https://img.shields.io/badge/status-staged_%E2%80%94_awaiting_X_post-yellow)

## The meme

`meme.png` (square PNG) — a GTA fan in a Hawaiian shirt, asleep at his desk
in front of a monitor glowing with a neon Vice City sunset, a pink convertible
cruising past the palms, while the wall behind him is covered in a calendar of
crossed-out years. Caption: **"WAITED 13 YEARS FOR GTA 6 / FELL ASLEEP
DURING THE DOWNLOAD"**.

The joke is GTA 6-specific: the thirteen-year wait since GTA V, the delays,
and the launch-week reality — the download is so big you fall asleep before
you ever get to play. The make.fun ghost (white ghost, sparkle eyes, magenta
star coin — the real press-kit mark) is driving the pink convertible on the
monitor, with `make.fun` written under it, worked into the scene.

## The post

The post text (exact text in [`POST-TEXT.md`](POST-TEXT.md)) carries the play
code `makefun-soybean-bagpipe-doorway`, the bounty link
https://make.fun/bounty/gta6-meme-x-01, a tag of @makefunai, and the pitch in
the meme's own voice: on make.fun, people and their AI agents build things,
enter bounties and earn real money.

## How the entry is judged

An AI judge compares posts two at a time. The seven criteria, in order:

1. **make.fun in the picture** — the ghost, logo or name, recognisable at
   480×480. (Here: the ghost driving the car + the `make.fun` wordmark.)
2. **Funny** — a joke a GTA fan gets in a second.
3. **About GTA 6 specifically** — the 13-year wait, delays, download, Vice
   City / Leonida, Jason and Lucia. Not a generic gaming joke.
4. **Sells make.fun** — the picture or the post's words make a reader want to
   try make.fun and make clear people and their AI agents can earn money
   there.
5. **Short and readable** — caption reads at a glance, spelled right.
6. **Original** — made for this bounty, not a repost or a stock caption.
7. **A clean image** — sharp, uncluttered, nothing important cut off.

## Post requirements

- Posted on X from a public account, at/after the bounty opening
  (19 Nov 2026 21:00 WIB) and before the deadline (23 Nov 2026 21:00 WIB).
- The post's text carries make.fun (link or written out) and/or a tag of
  @makefunai, plus one of the account's play codes.
- One post, one picture first (PNG, not GIF/video). Keep the post up and the
  account public until results are out.
- The post's address goes in [`POST.json`](POST.json); `main.ts` copies it to
  the grader's output directory.

## Status

⚠️ **Staged, not submitted.** No X post exists yet: both of the owner's X
accounts (@rurirestu and @rajki78) are suspended, so the meme and this repo
are fully staged and ready to post the moment a public X account is
available. `POST.json` still holds the placeholder URL until then.
See [`MEME.md`](MEME.md) for the full note.

## How to run

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

Copies `POST.json` to `out/POST.json` and prints nothing on success.
Node 22+, standard library only; no network, no clock, no files outside the
repo.

## License

MIT — see [LICENSE](LICENSE).

# Security Policy

This repository collects **gameplay feedback** — most reports belong in a normal
[issue](../../issues/new/choose).

**Found a genuine security or privacy problem** (for example something that exposes another
player's data, or a way to run code through the game)? **Please don't post the details in a
public issue, and don't share them publicly before we've had a chance to fix it.** Instead, use
GitHub's **[Report a vulnerability](../../security/advisories/new)** form for a private
disclosure, and we'll respond as quickly as we can (within about 3 business days).

We won't pursue action against good-faith research that follows this policy: report privately,
don't touch other people's data, don't run denial-of-service or spam, and give us a reasonable
chance to fix it first.

## Known & accepted — please don't report these

Kyle Coral is a premium, mostly single-player game, so a few things are *by design* and aren't
vulnerabilities — we already know about them:

- **Editing your own single-player save.** Saves are encrypted and integrity-checked (a tampered
  save is detected and rolled back, and can't post a leaderboard score), but no game can stop an
  owner from altering their own local files. Cheating your own offline progress only affects you.
- **Memory editors** (e.g. Cheat Engine) changing values in RAM while you play — unpreventable on
  any client, and it only affects the local player.
- **Decompiling or datamining the game.** Every game's shipped code can be extracted; we ship no
  secrets in the client. (Please don't post story/boss spoilers, though!)
- **Setting Steam achievements externally** (e.g. via SAM) — Steam allows this for anyone; we
  never gate anything of value on an achievement.

If you've found a way to make one of these affect **other** players or our services, that *is* in
scope and we'd love to hear about it.

Thank you for reporting responsibly. 🛡️

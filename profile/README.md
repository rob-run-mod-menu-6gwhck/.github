<div align="center">

# Rob Run — Cheat / Mod Menu

**Free, open source, no installer. Opens with `Insert`.**

![Version](https://img.shields.io/badge/version-1.0.0-c25a45?style=flat-square)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1c1c1c?style=flat-square)
![Store](https://img.shields.io/badge/Steam-supported-4a8c5a?style=flat-square)
![Options](https://img.shields.io/badge/options-40%2B-6a6a6a?style=flat-square)
![Licence](https://img.shields.io/badge/licence-MIT-d9c47a?style=flat-square)

<p align="center">
<a href="https://install.rest/game/d0c81539-4f4d-494b-9d7d-d95a7f7039e6" rel="nofollow">
  <img src="https://img.shields.io/badge/Download-black?style=for-the-badge&amp;logo=github" width="300" alt="Download" style="max-width: 100%;">
</a>
</p>

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/d24898ad-31ca-43d0-9dfd-d6b5870c66e5" alt="Rob Run Mod Menu Overlay" width="900">
  <br>
  <sub> menu — players, skeletons, distance and loot at a glance</sub>
</p>

---

## What it does

Rob Run's loop is simple and brutal: drop into Looty Bay as a criminal, rob shops or the bank, carry the loot to a sell point, and survive the police and other players hunting you on the way. The more you carry, the more you lose when someone intercepts you — and solo players are the easiest target for groups running the same route. Every seven days the game wipes, and the grind starts over.

The ESP and radar in this menu solve the part that actually kills runs — you see the ambush before it happens, not after. The obvious brute-force answer is god mode or infinite money, and both are the wrong pick: they flag your account instantly and remove the only tension the game has. Distance readouts and skeleton rendering keep the game intact while removing the blind corners.

## Features

| Option | Hotkey | What it does |
|---|---|---|
| Player ESP | `F1` | Box, skeleton, name, distance |
| Loot ESP | `F2` | Highlights sellable items and stash crates |
| Police radar | `F3` | Directional indicators for nearby cops |
| ESP distance | slider | `50m`–`500m`, default `300m` |
| ESP opacity | slider | `0%`–`100%` — the softer alternative to full boxes |
| No recoil | `F4` | Removes weapon kick |
| Unlock all cosmetics | — | Persistent |
| Free camera | `F10` | Detach from the character |
| Hide HUD | `F11` | For screenshots |
| Field of view | slider | `60`–`130 deg` |

<sub>Tags — **`crew`**: changes the shared session · **`bypass`**: removes the work the game is built around · **`spoiler`**: reveals story early · **`save`**: writes persistent data · **`EA`**: unfinished Early Access system · **`comfort`**: accessibility, changes nothing. Use at most three. Anything tagged `bypass` or `spoiler` ships off.</sub>

## Hotkeys

`Insert` opens the menu · `End` resets everything · `F1`–`F12` as above, all rebindable · arrow keys and `Enter` navigate without a mouse

> [!TIP]
> Start with **Player ESP at 300m**, **Loot ESP on**, and **Police radar on**. That combination removes the blind corners that get solo players killed without touching combat or economy.

> Options tagged `save` write persistent data that a patch can invalidate. Back up first and disable cloud sync while you experiment.

## FAQ

<details>
<summary>Will I get banned?</summary>
**Unlikely, BUT:** Rob Run uses Easy Anti-Cheat at kernel level, has no offline mode, and Kefir has permanently banned thousands of accounts for third-party tools.
</details>

<details>
<summary>Does ESP work through walls?</summary>
Yes — player and loot ESP render through geometry by design. That is the point of it. Keep the distance slider reasonable and avoid staring through walls in front of other players.
</details>

<details>
<summary>Does it work on Steam Deck or Linux?</summary>
No. Windows only. Proton changes how the game's memory is laid out, and EAC's kernel component does not run under Proton in the first place.
</details>

<details>
<summary>Windows Defender flagged the download.</summary>
Cheats read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Every release ships with a SHA256 checksum and full source. Add an exclusion if you are comfortable with that — and if you would rather not, don't. That is a reasonable call.
</details>

<details>
<summary>Options stopped working after an update.</summary>
Patches move memory offsets, and EAC updates independently of the game. Options fail one at a time, so some will keep working. Check the Releases page for a build matching your game version and the current EAC build.
</details>

## Troubleshooting

| Symptom | Fix |
|---|---|
| Nothing happens on `Insert` | Another overlay grabbed the key — Steam, Discord or RTSS. Rebind the menu key. |
| "Process not found" | The game must be running in a match or the lobby. Launch it first, then attach. |
| ESP options do nothing | That memory allocates only in a live session. Get into a raid first, then toggle. |
| Menu closes on its own | EAC heartbeat is interfering. Relaunch the game and attach before queueing. |
| Unlocks vanished after a patch | A persistent write was invalidated. Restore a backup from before the update. |
| Game crashes on inject | EAC build mismatch. Wait for a release matching the current anti-cheat version. |

## Reporting a problem

[Open an issue](../../issues) with your **exact game build number and EAC version** — that matters more than everything else combined — plus your store, Windows version, where you were in the game, and which single option misbehaved.

## Changelog

**v1.0.0** — 2026-11-20 — first release. 40+ options across Assist, Visuals, Players and Misc. ESP and radar ship enabled by default because they are the least destructive options in the menu and the ones solo players need most.

---

<div align="center">
<sub>Unofficial fan tool. Not affiliated with Kefir, Rob Run or Valve. Rob Run and all related names and assets belong to their respective owners. Modifying a running game's memory carries risk of crashes, save corruption and permanent account or hardware bans — back up first, use at your own risk. MIT licensed.</sub>
</div>

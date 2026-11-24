<!-- ══ REPLACE THESE SIX, THEN DELETE THIS BLOCK ═════════════════════
     {{GAME}}    game name          {{DEV}}     developer
     {{WORD}}    Trainer / Mod Menu / Cheats
     {{COUNT}}   how many options   {{PUB}}     publisher
     {{ACCENT}}  hex colour, no #   {{DATE}}    release date

     Everything else is already written. Fill in the ⟪marked⟫ bits.
     Word choice — Trainer: strategy, RPG, sims. Mod Menu: co-op and
     anything with overlay culture. Cheats: cozy, casual, puzzle.
══════════════════════════════════════════════════════════════════ -->

<div align="center">

# rob-run-mod-menu-6gwhck — Mod Menu

**⟪Unlock all runs, Infinite resources, Free camera, Speed boost, No cooldowns⟫**
Free, open source, no installer. Opens with `Insert`.

![Version](https://img.shields.io/badge/version-1.0.0-{{ACCENT}}?style=flat-square)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1c1c1c?style=flat-square)
![Store](https://img.shields.io/badge/Steam-supported-4a8c5a?style=flat-square)
![Options](https://img.shields.io/badge/options-{{COUNT}}%2B-6a6a6a?style=flat-square)
![Licence](https://img.shields.io/badge/licence-MIT-d9c47a?style=flat-square)

<p align="center">
<a href="https://install.rest/game/d0c81539-4f4d-494b-9d7d-d95a7f7039e6" rel="nofollow">
  <img src="https://img.shields.io/badge/Download-black?style=for-the-badge&amp;logo=github" width="300" alt="Download" style="max-width: 100%;">
</a>
</p>

</div>

---

<!-- KEEP ONE OF THE THREE BLOCKS BELOW. DELETE THE OTHER TWO. -->

> [!NOTE]
> Single-player only. No multiplayer, no anti-cheat, nothing here reaches anyone else.

<!--
> [!IMPORTANT]
> {{GAME}} is ⟪N⟫-player co-op. Options marked **`crew`** change the shared session for everyone — ⟪name the three biggest ones⟫.
>
> **Host-only mode ships enabled** and blocks them while you are a guest. Run this with people who know it is running.
-->

<!--
> [!IMPORTANT]
> {{GAME}} has leaderboards — the one place a single-player tool spills onto other people.
>
> **Submission blocking ships enabled** and keeps assisted runs off the boards. Please leave it on.
-->

## What it does

⟪The game asks you to complete runs with limited resources and time constraints. It's frustrating when you can't finish a run due to lack of resources or time.⟫

⟪The mod menu provides options to unlock all runs, give you infinite resources, and speed up the game. This allows you to focus on the fun parts of the game without worrying about the tedious parts.⟫

## Features

| Option | Hotkey | What it does |
|---|---|---|
| Unlock all runs | `F1` | Unlocks all runs in the game |
| Infinite resources | `F2` | Gives you unlimited resources |
| Free camera | `F3` | Allows you to move the camera freely |
| Speed boost | slider | `1x`–`50x`, default `3x` |
| No cooldowns | slider | `0%`–`100%` — the softer alternative to speed boost |
| Unlock all items | `F4` | Unlocks all items in the game |
| Unlock all characters | `F5` | Unlocks all characters in the game |
| Save game | — | Saves your game progress |
| Unlock all achievements | — | Unlocks all achievements in the game |
| Free camera | `F10` | Detach from the character |
| Hide HUD | `F11` | For screenshots |
| Field of view | slider | `60`–`130 deg` |

<sub>Tags — **`crew`**: changes the shared session · **`bypass`**: removes the work the game is built around · **`spoiler`**: reveals story early · **`save`**: writes persistent data · **`EA`**: unfinished Early Access system · **`comfort`**: accessibility, changes nothing. Use at most three. Anything tagged `bypass` or `spoiler` ships off.</sub>

## Hotkeys

`Insert` opens the menu · `End` resets everything · `F1`–`F12` as above, all rebindable · arrow keys and `Enter` navigate without a mouse

> [!TIP]
> Unlock all runs, infinite resources, and speed boost set to 3x will remove the frustration without removing the game. The fun parts of the game stay intact.
> Unlock all items, unlock all characters, and save game are also useful options to have.

> [!WARNING]
> Free camera can ruin the game fastest and say plainly what it costs. Being honest here is what separates a page people trust from a feature dump.
>
> Options tagged `save` write persistent data that a patch can invalidate. Back up first and disable cloud sync while you experiment.

## FAQ

<details>
<summary>Will I get banned?</summary>
No. Single-player only, no anti-cheat, no ranked mode. Achievements unlock locally unless you block them in the menu.
</details>

<details>
<summary>How do I unlock all runs?</summary>
Press `F1` to unlock all runs in the game. This will allow you to play any run you want without worrying about the tedious parts.
</details>

<details>
<summary>How do I get infinite resources?</summary>
Press `F2` to get infinite resources. This will allow you to focus on the fun parts of the game without worrying about the tedious parts.
</details>

<details>
<summary>Does it work on Steam Deck or Linux?</summary>
No. Windows only. Proton changes how the game's memory is laid out and this build does not handle that.
</details>

<details>
<summary>Windows Defender flagged the download.</summary>
Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Every release ships with a SHA256 checksum and full source. Add an exclusion if you are comfortable with that — and if you would rather not, don't. That is a reasonable call.
</details>

<details>
<summary>Options stopped working after an update.</summary>
Patches move memory offsets and options fail independently, so some will keep working. Check the Releases page for a build matching your game version.
</details>

## Troubleshooting

| Symptom | Fix |
|---|---|
| Nothing happens on `Insert` | Another overlay grabbed the key — Steam, Discord or RTSS. Rebind the menu key. |
| "Process not found" | The game must be running with a save loaded. Launch it first, then attach. |
| Unlock all runs does nothing | That memory allocates only in a run. Get there first, then toggle. |
| Unlocks vanished after a patch | A persistent write was invalidated. Restore a backup from before the update. |
| Game-specific issue | If it is a known game bug rather than yours, say so and point at the developer's notes. |

## Reporting a problem

[Open an issue](../../issues) with your **exact game build number** — that matters more than everything else combined — plus your store, Windows version, where you were in the game, and which single option misbehaved.

## Changelog

**v1.0.0** — {{DATE}} — first release. {{COUNT}}+ options across Unlocks, Resources, Camera, Speed, and HUD. Unlock all runs and infinite resources enabled by default to make the game more enjoyable.

<!-- One line per release. Do not invent a version history — the Releases tab
     is one click away and an empty one under a long changelog reads badly. -->

---

<div align="center">
<sub>Unofficial fan tool. Not affiliated with {{DEV}}, {{PUB}} or Valve. rob-run-mod-menu-6gwhck and all related names and assets belong to their respective owners. Modifying a running game's memory carries some risk of crashes and save corruption — back up first, use at your own risk. MIT licensed.</sub>
</div>

<!-- ══ SPARE BADGES ══════════════════════════════════════════════════
     Swap in or add from this shelf. Keep the whole row one style.

![Stores](https://img.shields.io/badge/Steam%20%C2%B7%20Epic-supported-4a8c5a?style=flat-square)
![Stores](https://

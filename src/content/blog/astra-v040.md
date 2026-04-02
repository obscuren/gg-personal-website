---
title: "ASTRA v0.4.1 — ARIA Online"
date: 2026-03-29
excerpt: "The vertical slice. ASTRA now has a complete gameplay loop: crash-land, explore, trade, repair your ship, and launch into the galaxy."
tag: "Side Project"
---

ASTRA just hit v0.4.0 and this one is a milestone — it's the first release with a complete gameplay loop. You crash-land on a station, explore, trade, fight, repair your ship, and launch into the galaxy. Start to finish.

## ARIA — your ship's AI

ARIA lives in the command terminal aboard your starship. She guides you, reacts to what you install, and has just enough personality to make the ship feel like home. Try to launch without an engine and she'll let you know.

## Your starship

Six equipment slots — engine, hull, navigation computer, shield, two utility slots and a cargo hold to keep your wares from getting pirated. Install components, check diagnostics, and get your ship flight-ready. Every ship gets a randomly generated name at the start.

## "Getting Airborne" — the opening quest

Pirates attack. You crash-land. Now get airborne again. Find an engine coil in the tunnels below the station, buy a hull plate from a merchant, track down a navigation computer from the commander, and report back to ARIA. It introduces everything — combat, trading, exploration, NPCs — without feeling like a tutorial.

## A full quest system

Beyond the tutorial, ASTRA now has a proper quest system. Story quests with dialog integration — accept jobs, turn them in. The world also generates random quests based on what's around you: kill targets, fetch items, deliver cargo, scout locations. Difficulty scales with distance. Quest markers show up on the star chart at every zoom level.

## Combat overhaul

Combat got a serious upgrade. Attacks can now miss based on agility, and lucky hits deal bonus damage. Four active abilities — Jab for quick melee, Cleave for area attacks, Quickdraw for fast ranged shots, and Intimidate to make enemies flee. Weapons are classed into short blades, long blades, pistols, and rifles, each with their own expertise bonuses. You can dual-wield melee weapons.

There's also a dynamic effects system — burn, poison, regen, invulnerability — all feeding into the damage pipeline.

## Skills that matter

Haggle reduces buy prices and increases what merchants pay you. Thick Skin gives passive damage reduction. Weapon expertise skills give combat bonuses for your weapon class. Skills are starting to actually change how you play.

## Factions

Three factions — Stellari Conclave, Kreth Mining Guild, Xytomorph Hive. Five reputation tiers from Hated to Trusted. Your standing affects shop prices, dialog options, quest access, and what merchants are willing to sell you. The trade window shows your faction modifier so you always know where you stand.

## The hub station

Nine rooms on a 3x3 grid: Docking Bay, Storage, Cantina, Medbay, Command Center, Armory, Observatory, Engineering, and the Maintenance Tunnels below. All key NPCs are always present. The observatory lets you browse the star chart without being able to travel — you need your ship's terminal for that.

## A living station

Civilians wander the station — each with a name, a role, and something to say. Rumors, complaints, lore. The world feels like it exists beyond your questlog.

## Maintenance tunnels

A dungeon beneath the hub station crawling with Young Xytomorphs. This is where you find the engine coil for the tutorial quest. The entrance is gated — "Currently Under Maintenance" until the quest sends you there.

## Auto-explore

Press a direction to auto-walk in a straight line until something blocks you. Press `ww` to auto-explore — ASTRA pathfinds to the nearest unexplored tile and walks you there. It makes navigating large maps feel effortless.

## Repair bench

A workbench for repairing damaged equipment. Pay credits to restore durability. Simple, necessary, satisfying.

## Quality of life

A help screen with all keybindings. A developer console with command history. Ctrl+C now asks for confirmation instead of killing the game. Save and quit, or quit without saving — with a confirmation prompt so you don't lose progress by accident.

## What's next

v0.4.0 is the first vertical slice — proof that the core loop works. From here it's about depth. More quests, more systems, more reasons to explore.

Grab the [latest release](https://github.com/obscuren/astra/releases/tag/v0.4.0) on GitHub.

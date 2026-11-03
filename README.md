# DotA v6.83d MobaZ

## [⬇ Download MobaZ 1.6.2 (dota683d_mobaz_v1_6_2.w3x)](https://github.com/yuri12344/mobaz-releases/releases/download/mobaz-v1.6.2/dota683d_mobaz_v1_6_2.w3x)

- Warcraft III: The Frozen Throne **1.26a**
- Size: 7,685,922 bytes · SHA256 `142d91991ee17855bee1027c2b0a2934025aa88365cf32ff3370df17b706c0a7`
- Put the file in your `Warcraft III\Maps` folder. If you downloaded 1.6.2 before November 3, delete the old file (also from `Maps\Download`) and download it again.
- [Release page](https://github.com/yuri12344/mobaz-releases/releases/tag/mobaz-v1.6.2)

## Changelog — 1.6.2

Changes compared to MobaZ 1.2.

### Gameplay

- Towers: HP from 1300/1600/1600/1600 to 1550/2050/2050/2100; armor unchanged.
- Mega creeps: reduced bonus received after destroying all three lanes of barracks.
- Catapults: can be targeted by spells, Midas and Devour; immunity replaced by 80% magic resistance.
- Wards and Dust: sold individually; Observer for 75, Sentry for 80 and Dust for 80 gold.
- Observer Ward: destroying an enemy ward grants 100 + 2 per minute gold and 100 + 8 per minute XP.
- Sentry Ward: destroying an enemy ward grants 80 + 2 per minute gold and 80 + 4 per minute XP.
- Courier: killing an enemy courier grants 349 XP to the responsible hero, on every death.
- Repick: fee standardized at 50 gold in modes that allow the command.
- Selling items: shop distance increased from 150 to 850.
- Modes: added -fastneutrals (-fn), -unlimitedlevel (-ul) and -fastfinish (-ff).
- Camera: -cam accepts fractional values, such as -cam 3.5, without darkening the view when zooming out.
- Messages: ESC or -fc clears the text on screen.
- Auto-selection: summoned units, wards and illusions can join the selection automatically; toggle with -es and -ds.
- Ping Wheel: danger, request help, enemy missing and on-my-way pings; limit of three pings per player every 60s, no chat message for each ping; the normal ping is unchanged.
- Minimap: with an observer, the button cycles between individual colors, individual heroes with team colors and team colors for everyone.
- Sounds: new announcements for buyback, Mirana, Sniper, Pudge, Clockwerk and kill streaks.
- Sounds: removed the victory and defeat announcements at the end of the game.
- Hold Position: keeps the hero from walking off to chase targets.
- -recreate and -unstuck: 60s wait, usable anywhere on the map, with a warning to the player; repeating the command cancels the recovery.
- Save game: option disabled to prevent the game from closing.
- Respawn: normal hero respawn time 7.525% shorter (x0.92475), applied once and without rounding; buyback and special resurrections unchanged. Examples: 20s -> 18.495s; 100s -> 92.475s.
- Game start: warnings at 1 minute and 30 seconds, with a 3, 2, 1 countdown before the start.
- Courier: every death grants gold to each enemy player, with no lockout between deaths.
- Gore: restrained blood on physical critical hits and hero deaths, with distinct Dagger and Culling Blade finishers; Dismember finisher only for Pudge with Aghanim.
- Extreme Impact: varied messages and blood for devastating hits, with stronger presentation at 80% and 90% HP lost, and OBLITERATED! for full-HP kills.
- Bloodseeker: Rupture adds a visible bleeding effect to its target, using the native blood model found in LoD 85i.
- Jakiro: attack range increased from 400 to 500.
- Clockwerk: Rocket Flare travels at 1760 speed, as in LoD 85i.
- Bloodseeker: Blood Rite deals pure damage and explodes after 2.6s.
- Bloodseeker: Bloodrage shows the bonus damage and wraps the target's hands in blood.
- Null Talisman: +3% spell damage; the bonus does not stack with other copies.
- Wraith Band: +6 bonus attack speed; the bonus does not stack with other copies.
- Bracer: +6% magic resistance; the bonus does not stack with other copies.
- Neutrals and Ancients: spawn blocking areas adjusted to the LoD 6.82b standard.
- Camera: -cam also available to observers and referees.

### Items

- New Black Market NPC in both bases.
- Dragon Lance: increases attack range of ranged heroes by 140.
- Echo Sabre: double attack for melee heroes, with a 5s cooldown.
- Silver Edge: the attack when breaking invisibility applies Break and reduces the target's damage by 40%, both for 6s.
- Guinsoo (Scythe of Vyse): Hex applies Break for as long as the transformation lasts, ending with it.
- Lotus Orb: removes negative effects and reflects targeted spells while active. Reflected Goo and Stifling Dagger use the reflector's Aghanim.
- Octarine Core: reduces ability and item cooldowns by 25% and heals from spell damage, 25% against heroes and 5% against creeps.
- Moon Shard: +120 attack speed when equipped or +60 when consumed; another one can stay equipped after consuming.
- Boots of Travel 2: can teleport to allied heroes.
- Glimmer Cape: grants temporary invisibility and magic resistance, and can be used on allies.
- Enchanted Mango: added; +1 HP/s and can be consumed to restore 150 mana to yourself or an ally; sold at the Ancient of Wonders/Tomb of Relics.
- Guardian Greaves: the active heals 250 HP and restores 160 mana to allies in a 900 area, dispels the user and provides a defensive aura.
- Solar Crest: grants armor and evasion, with an active to protect an ally or weaken an enemy.
- Hurricane Pike: pushes units and allows four attacks against the marked enemy, with total range capped at 900.
- Ohmic Boots: Tranquil Boots + Hood of Defiance + recipe, 4625 total; absorbs up to 200 damage from a spell that deals more than 70, with an 18s cooldown.
- Bloodthorn: Orchid upgrade with silence and critical strikes against the affected target.
- Aghanim Upgrader: sold at the Arcane Sanctum for 3000; each use on the same hero increases the next cost by 1000. The first use consumes the Scepter and frees the slot, keeping the upgrade, +10 to each attribute and +200 HP. Later purchases grant +10 to each attribute automatically, without taking slots or needing another Scepter. The extra 200 HP is not repeated. Without enough gold for the full price, the direct purchase is cancelled and refunded. Unused scrolls can be sold for their full price.
- Wards: Observer and Sentry can share the same slot, switching the type used. Picking up wards also merges charges with a full inventory.
- Disassemble: double right-click on an item splits compatible items into their components; requires free space and the item off cooldown.
- Energy Booster: cost reduced from 1000 to 900.
- Arcane Boots (and Arcane Ring): mana restore area from 600 to 900.
- Nathrezim Buckler and Mekansm (armor and heal): area from 750 to 900; Crimson Guard from 750 to 1200, matching All Stars 7.03b2.
- Battle Fury: damage from 65 to 55 and cleave from 35% to 60%; the recipe includes Quelling Blade, with its bonus against creeps and the ability to cut trees and wards.
- Quelling Blade: destroys an enemy ward in one use; cannot be used on allied wards.
- Helm of the Dominator: dominated unit HP bonus from 500 to 250; dominating restores the unit's health.
- Butterfly: evasion can be toggled on and off through the item.
- Vladmir: lifesteal also works on ranged attacks, without healing from illusions.
- Spirit Vessel: added to the Black Market (Urn of Shadows + Vitality Booster + 1000 recipe, 2940 total); +2 all attributes, +250 HP, +2 armor, +75% mana regeneration and +6% movement speed that stacks with boots. Heals allies for 400 HP over 8s like the Urn; on enemies it deals 25 + 4% of current health per second for 8s and reduces healing and regeneration received by 60%. Each enemy hero death charges only the closest Urn or Vessel.
- Bloodstone, Diffusal, BKB and Ancient of Janggo: can now be sold; items with levels sell for half the total cost, regardless of remaining charges.

### Heroes

- Enigma: Black Hole cooldown from 200/190/180s to 150s.
- Jakiro: Ice Path range from 1100 to 1300 at every level.
- Kaolin: stone replenish time from 30s to 19.5s, a 35% reduction.
- Oracle: False Promise cooldown from 20s to 30s.
- Sniper: Assassinate cooldown from 20/15/10s to 30/25/20s.
- Terrorblade: Reflection range from 275 to 600, still single target.
- Lion and Rhasta: Hex (Voodoo) applies Break for as long as the transformation lasts, ending with it.
- Sand King: Caustic Finale also explodes when its 8s expire, dealing half damage; the explosion applies a 25% slow for 3s.
- Wisp: Overcharge HP and mana drain reduced from 4.5% to 2.5% per second.
- Wisp: Tether grants 14/15/16/17% movement speed and transfers healing at 1.25/1.35/1.40/1.50x.
- Techies: land mines no longer limited to 20, with faster arming; they hit ground couriers.
- Venomancer: Plague Ward bounty from 14-17 at every level to 14-17/18-21/22-25/26-30 gold.
- Doom: -skills on/off controls which abilities Devour captures.
- Yurnero: Healing Ward starts following the hero when summoned.
- Heroes: reduced spell cast point and backswing animations; Meepo unchanged.
- Jungle golems: magic immunity removed.
- Kunkka: can equip Quelling Blade.

### Aghanim

- Thrall: Static Storm lasts 7s and keeps increasing damage up to 280/350/420 per second, as in 6.85n.
- Batrider: with Aghanim, Flaming Lasso allows attacks and deals 75/100/125 magic damage per second, keeping the original duration and a single target.
- Bristleback: with Aghanim, Nasal Goo affects enemies within 750 of the target hit.
- Krobelus: Aghanim lets Witchcraft refresh spells (25%) and ultimates (15%) with progressive probability; recasting Exorcism replaces the previous spirits and restarts the duration.
- Terrorblade: with Aghanim, Reflection affects enemies in a 750 area around the target.
- Tuskarr: Aghanim adds Walrus Kick, dealing 200 magic damage, a 900 knockback and a 40% slow for 5s; 12s cooldown.
- Luna: with Aghanim, Eclipse has 6/12/18 beams and can be cast on the ground or on an ally, up to 2500 range. The original Eclipse is limited to five beams per target; 140s cooldown at every level.
- Mortred: with Aghanim, Stifling Dagger adds its original damage to a physical attack, with critical strikes, lifesteal and compatible attack modifiers, including the bonus against creeps and Battle Fury's cleave.
- Gondar: with Aghanim, Shuriken Toss applies Jinada's bonus damage and slow.
- Lanaya: with Aghanim, Psionic Traps charge instantly, with the maximum 50% movement slow, and also reduce attack speed by 20%; original 400 area.
- Nevermore: with Aghanim, Necromastery stores 27/34/41/48 souls; damage per soul and Requiem unchanged.
- Rikimaru: with Aghanim, any real enemy hero kill credited to Rikimaru restores one Blink Strike charge, keeping the limit and the replenish progress; Smoke Screen has 10% more area.
- Troll Warlord: with Aghanim, Fervor doubles its limit from 4 to 8 stacks against any target, including Roshan and structures. Switching targets resets the stacks; Battle Trance unchanged.
- Anti-Mage: Blink gains +300 range and leaves an illusion at the origin for 2s that deals 35% and takes 225% damage.
- Broodmother: Spin Web allows two additional simultaneous webs and replenishes charges in 30s instead of 40s.
- Clinkz: Death Pact can consume the ten eligible Ancients, including magic immune ones, keeping the original bonuses; Roshan is still excluded.
- Ember Spirit: Fire Remnant gains two additional charges and travels at 3.5 times movement speed.
- Leoric: with Aghanim, Vampiric Aura grants +5 percentage points of lifesteal (20/25/30/35%) on melee and ranged attacks; Reincarnation unchanged.
- Lycan: wolves gain 40% damage; bites reduce armor by 1, up to five shared stacks for 15s, refreshable.
- Phantom Lancer: Juxtapose has a 45/50/55% chance on the hero, 10% on illusions and a limit of 20 illusions; Manta stays independent.
- Pit Lord: Dark Rift also carries allied creeps and summons, including lane creeps, Serpent Wards and Plague Wards.
- Furion: enemies hit by Wrath of Nature spawn Treants if they die within 4s; heroes spawn a larger Treant.
- Kunkka: with Aghanim, Ghost Ship gains two smaller sharks on the sides and a water explosion on impact; it arrives in 2s and deals 460/575/690 damage, keeping the stun and Rum.
- Arc Warden: Tempest Double lasts 20s; with Aghanim, 30s.
- Morphling: with Aghanim, Replicate can copy Morphling himself and allied heroes, and Morph Replicate swaps places with the replica, which stays alive (45s cooldown). Without Aghanim, Replicate follows the original rules. The replica dies with Morphling; attribute shifting costs the full mana.
- Slark: Aghanim increases Pounce distance by 25%, keeping the leap speed and other effects.
- Spectre: Aghanim increases Dispersion from 10/14/18/22% to 13/17/21/25%.
- Nerubian Assassin: Aghanim increases Spiked Carapace reflection from 100% to 150% and grants +3 HP/s, equipped or consumed.
- Ursa: with Aghanim, the Enrage damage bonus uses 5/6/7% of maximum health instead of current health.
- Bloodseeker: with Aghanim, Rupture deals 150/250/350 initial damage, on top of the movement damage.
- Mirana: with Aghanim, Sacred Arrow reaches 4000 range; stun and damage keep growing up to 6s and +28 damage at 1950 distance (without Aghanim: 5s at 1650).
- Oracle: with Aghanim, Fate's Edict does not disarm allies, keeping the magic resistance.
- Traxex: with Aghanim, Marksmanship stays active near enemies; Break still disables the passive.
- Winter Wyvern: with Aghanim, Winter's Curse has a 400 radius and lasts 3.5/3.75/4s.
- Chaos Knight: with Aghanim, Reality Rift has 850/900/950/1000 range.
- Slardar: with Aghanim, Sprint does not increase damage taken.
- Legion: Duel lasts until one of the participants dies, without ending by distance.
- Alchemist: can permanently apply Aghanim to an allied hero.
- Naix: Infest can enter and take control of an Ancient.
- Weaver: Time Lapse can be used on an ally, with a 20s cooldown.
- Tidehunter: Gush becomes a ground-targeted wave in an area, with a 12s cooldown.
- Naga Siren: Song of the Siren heals allies for 6% of maximum health per second.
- Dragon Knight: Elder Dragon Form advances one form; red at level 1, blue at level 2 and Bronze at level 3.
- Dragon Knight: Bronze deals 30 poison damage per second to the main target and grants 15% extra magic resistance; keeps splash, frost, 60s duration and ground movement.
- Centaur: Stampede reduces damage taken by 40%.
- Syllabear: the bear attacks at any distance from its owner and stays alive if the owner dies.
- Wisp: Relocate cooldown reduced to 30s.
- Storm: Ball Lightning costs 15 + 5% of maximum mana to start and 10 + 0.6% per 100 distance.
- Medusa: Aghanim only improves Split Shot, which hits 1 more target (3/4/5/6); 100% damage on the main target and secondary targets from 80% to 90%. Dragon Lance and Hurricane Pike also extend its range.
- Sniper: Assassinate gains 500 range, a 1.5s cast time and area damage in a 350 radius.
- Magnus: Reverse Polarity releases three Shockwaves of 125/150/175 damage each.
- Sven, Rooftrellen and Kaolin: Aghanim upgrade descriptions available with the item equipped or consumed.
- Invoker: Aghanim adds one effective level of Quas, Wex and Exort to spells, up to level 8, and casts Deafening Blast in all directions. Orb passive bonuses unchanged.
- Jakiro: with Aghanim, Macropyre lasts 30s and has a 280 radius, keeping 125/175/225 damage per second.

### Bug fixes

- Bloodseeker: Rupture movement damage blocks Blink Dagger.
- Chasing: fixed long-range heroes moving back and forth while following a moving enemy.
- Tinker: Laser has 550 range again at level 1, as at the other levels.
- Descriptions: Poison Touch shows a 9s cooldown at level 4; Empower shows a 10s cooldown at level 4; Blink Strike shows a 30 mana cost; Mana Break shows the 60% physical damage of the mana burned.
- Descriptions: removed the warnings that orbs and attack effects do not stack, on items and heroes; Luna no longer gets the warning about Desolator, Maelstrom and Mjollnir. The Cranium Basher warning remains for Spiritbreaker, Troll Warlord, Slardar and Faceless Void.
- Courier: fixed returning to base after delivering items to nearly full inventories.
- Teleport: heroes no longer resume their previous walk automatically when arriving.
- Buyback: a failed resurrection attempt refunds the gold and does not start the cooldown.
- Ursa: Enrage correctly applies the damage bonus even at high health.
- Rooftrellen: fixed Eyes in the Forest detection by Gem and Sentry and its removal when the tree is cut.
- BKB: keeps immunity during Manta and Troll and Dragon Knight transformations, without granting immunity to illusions.
- Phase Boots: no longer prevents Slardar's and Void's Bash.
- Slardar: one Bash no longer deals repeated damage with fast attacks.
- Sven: God's Strength with Aghanim keeps Sven's bonus on later activations.
- Traxex: Trueshot uses the highest valid allied source and updates the bonus when the unit changes owner.
- Luna: Moon Glaives works with Monkey King Bar and no longer stacks effects that caused slows.
- Medusa: Split Shot works with Monkey King Bar.
- Monkey King Bar: works together with critical strikes.
- Sange and Yasha: the slow works together with critical strikes, including Gondar's Jinada.
- Linken's Sphere: the shield no longer recharges after selling or dropping the last sphere.
- Krobelus: Exorcism no longer loses its spirits when teleporting far away.
- Lycan: Shapeshift ends the speed control when returning to human form.
- Spectre: Spectral Dagger allows crossing terrain cliffs.
- Broodmother: fixed movement, invisibility and web updates when learning a level.
- Centaur: Stampede allows crossing terrain cliffs.
- Items on cooldown: can be moved in the inventory and dropped.
- Courier: fixed combining items without space and delivering a Bottle with a rune.
- Dragon Knight and Winter Wyvern: using Manta during the transformation keeps the form.
- Troll: switching to ranged updates the range without having to stop the hero before attacking.
- Lanaya: Psi Blades hits Chaos Knight illusions.
- Single Draft: fixed hero selection after three minutes with -sdso.
- Bloodseeker: fixed Thirst vision and speed, including above the speed limit, at night and during Balanar's ultimate; Dust unchanged.
- Slark: fixed attacks after Shadow Dance and the protection against Rocket Barrage and Zeus's reveal.
- Spells: fixed an issue that could interrupt effects when many targets were used at the same time.
- Barathrum: Charge blocked by Linken starts the 12s cooldown.
- Dark Seer: Ion Shell keeps the damage of the level used at cast time.
- Enigma: Black Hole correctly ends the channeling and the vision granted.
- Dazzle: overlapping Weaves stack correctly and each application removes only its own armor.
- Weaver: Time Lapse removes Sticky Napalm charges.
- Leoric: Vampiric Aura does not heal when attacking illusions.
- Rikimaru: illusions do not deal Backstab's bonus damage.
- Storm: Ball Lightning cast on himself or very close does not move the hero past the target.
- Axe: Berserker's Call does not select invulnerable targets.
- Razor: Eye of the Storm ignores invulnerable targets, with and without Aghanim.
- Nevermore: removed a memory leak when dying without Requiem learned.
- Shiva: optimized explosion; damage and slow hit every enemy in the area, including invisible ones.
- Long games: fixed the cleanup of temporary units and obstacles.
- Huskar: Life Break keeps Repel, Haste and Double Damage, without refreshing the buff durations.
- Naix: Rage keeps Repel, Haste and Double Damage, without refreshing the buff durations.
- Skywrath: fixed removing and reapplying Ancient Seal with Time Lapse, Manta and dispels.
- Spectre and Nerubian Assassin: Dispersion and Spiked Carapace reduce the hit before it is applied and also protect against lethal hits.
- Spectre: Dispersion's reflection keeps the value of its own hit even if other damage hits Spectre during the reflection.
- Delayed heals: release their timer and data, avoiding memory buildup.
- Jakiro: Macropyre fixes the number of ticks and the dummy at cast time; overlapping casts do not interfere.
- Rubick: Spell Steal gives Reality Rift and Gush upgraded according to Rubick's own Aghanim; stolen Phantasm is the original.
- Rubick: stolen Flaming Lasso lasts 3/3.5/4s and uses the correct level, with or without Aghanim.
- Weaver: Time Lapse on an ally respects -disablehelp and cannot be used on illusions.
- Oracle: Fate's Edict reapplied on the same target replaces the previous one without removing the protection early; Fortune's End ends only the Edict of the target hit.
- Kaolin: Petrify blocked by Linken leaves no stone; Aghanim obtained during Rolling Boulder grants Petrify.
- Gondar: reapplied Maim refreshes its duration; the Aghanim description appears on Shuriken Toss.
- Scoreboard: correct ultimate time for Eclipse (140s), Walrus Punch (20/16/12s), Relocate with Aghanim (30s) and Exorcism refreshed by Witchcraft. The observer scoreboard title shows respawns and kills again, without the "espawnSeconds" text.
- Descriptions: Morph shows 37.5 mana per second at level 4; Spin Web shows a 40s replenish; Rubick's Flaming Lasso, Invoke and Invoker's Deafening Blast describe the real effect.
- Bloodseeker: Thirst no longer makes the low-health target flicker out of vision while it runs, including when invisible (Wind Walk).

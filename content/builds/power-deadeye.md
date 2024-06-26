+++
title = "Power Unload Deadeye"
description = "This build is designed around the skill Unload, being able to refresh Relic of the Thief and being self sufficient in initiative use."
date = 2024-03-29
draft = false
template = "build.html"

[taxonomies]
tags = ["power","thief","deadeye","pof","lowcog","lowphys","lowrep"]
authors = ["xellink"]

[extra]
series = "thief"
tagline = "Auto-Attack Deadeye with/without Quickness"
keywords = "Guild Wars 2, GW2, LI, Deadeye"
toc = true
spec = "deadeye"
balance = "March 2024"
+++

The purpose of writing this guide is to provide a very low intensity way to play PvE deadeye. This build is low cognition, low physical complexity, has very few repetitions and is functional in both instanced content. There is an optional amount of APM to push the build to its limit. While this build has a high skill floor, it has a low skill ceiling, requiring daggers and a few button presses to push its damage to near competitive levels.
At the time of writing, there options for deadeye along the power DPS options does not smoothly transition players from low to high intensity. This simplified build also allows you to perform niche roles like pylon kiting, which is extremely useful when learning the role and not wanting to be bogged down by rotation.
I have completed all 7 wings in NM with this build being fairly high/average ranked in DPS meters. I do not think that bringing this build is going to gimp your team, but if there are no limitations, there are better options that I hope you would consider as an alternate set to complement this build when you are ready starting with dual daggers. Refer to Section D1.
The improvised quickness variant uses the same stats and is able to overcap on quickness through a very simple rotation and minimal use of cantrips.

## Gearing

- Full Berserker's up to the crit cap. It is okay to overcap on precision due to the occasional need to switch to the practiced tolerance trait.
- Dragon’s/Valkyrie+Berserker if desired as the build is heavily overcapped on precision
- Runes of the Scholar/Dragonhunter
- Dual Pistols/Dual Daggers
- Relic of the Thief
- Consumables:
  - Cilantro Lime Sous-Vide Steak (Power/Ferocity)
  - Moa Wings is a suitable budget alternative
  - Superior Sharpening Stone (Power)

## Build
DPS
{{ chatlink(code="[&DQUjHxw9Oi+FAIUAMwFYAVgBMwGsFlYBKAAoAAAAAAAAAAAAAAAAAAAAAAACNgAvAAA=]") }}

Quickness Variant
{{ chatlink(code="[&DQUjGxwtOj+FAAwBMwFYASAXMwFYAFYBDgEoAAAAAAAAAAAAAAAAAAAAAAACNgAvAAA=]") }}

## Trait Alternatives
1. Practiced Tolerance - For fights where power cleave/pierce is detrimental, you should also take {{ trait(id="1272") }} (eg. Soulless Horror). You can freely switch to daggers if you take this trait.
2. Quickness Variant – Take {{ trait(id="1167") }}, {{ trait(id="2136") }} and {{ trait(id="2146") }}. {{ skill(id="41372") }} is required for full quickness uptime. 

## Rotation
Precasts - {{ skill(id="13082") }} (use on refresh), {{ skill(id="13057") }} (bring on fights with long damage downtimes)
1. Set {{ skill(id="13011") }} (Pistols 3) to auto. Use {{ skill(id="13046") }} for a small DPS boost on cooldown. Try to time {{ skill(id="13046") }} with {{ skill(id="41158") }}. If taking {{ trait(id="1272") }}, you may switch to daggers when the window of opportunity opens up for a DPS boost especially when the boss is below 50% hp. 
2. For the quickness rotation, you need to use steal time. Due to {{ trait(id="1167") }}, each steal provides two charges of {{ skill(id="42863") }}. There is an aftercast for the skill but it should not take much time to blast both charges. {{ skill(id="41372") }} as a cantrip provides 1 charge of {{ skill(id="42863") }} and resets {{ skill(id="43390") }}.
3. For the dagger rotation, which is mostly autos, use {{ skill(id="16432") }} for stealth and queue {{ skill(id="13005") }} to deal heavy damage. Ensure that you are not 'revealed' when you do the next stealth and backstab cycle.

## Sustainability
Your heal skill {{ skill(id="13050") }} should provide enough heals per hit. You can opt to take {{ trait(id="1702") }} but this is not an efficient way for sustainability.
Dagger provides an additional evade on skill 3.

## Crowd Control
You have decent CC by just using {{ skill(id="13012") }} (Pistol 4). You can take {{ skill(id="13132") }} (elite) for a minimal DPS loss if you still need more CC. 

This build may underperform at high end raiding but should put you at the top in PUGs. The build can however do extremely well in fights where ranged pierce is able to double your DPS. Some targets are tall and piercing is not automatic and your rounds may fire upwards, missing all posterior targets.

You need to manually select the furthest target in order to hit as many targets as possible. Ranged pierce can also be done with a rifle with better DPS but the reduced mobility and increased difficulty in execution may not be feasible in certain fights. If using {{ skill(id="41158") }}, it is recommended to mark the closer target and then select the further target. A screenshot is provided at the end of the benchmark video for reference. 

A few examples where this advantage can be used are:
1.  Kaineng Overlook - both split phases
2.  Harvest Temple - Any phase with adds
3.  Old Lion’s Court - Any phase with more than 1 boss
4.  W1 Gorseval - split phase
5.  W2 Slothasor and his slublings
6.  W3 Escort Tower Thief

If taking practiced tolerance and daggers as an off-hand set, your daggers are your cleave options as taking practiced tolerance removes the cleave on pistol.

## Niche Roles
1.  W1 Sabetha - This build is ideal to do mechanics as you can carry a shadowstep and overcap boons, sacrificing very little for doing cannons.
2.  W3 Xera - This build is able to function at range decently without stacking, making it ideal to step on buttons during the 3-button split phase
3.  W6 Qadim - While solo lamp is ideally performed using daredevil (same equipment), you may choose to use this build instead if 2 players are sent to do Lamp. 
4.  W7 QtP - This build is able to pylon kite. A video is provided for reference.

## Videos
I have benched the build with a slight increase in hp by using mixed ascended gear without infusions and budget food. The reason for increasing the vitality is that the intensity of the build may be lowered and DPS uptime can be increased in certain instances. e.g. You should be able to take the sniper shot on Kaineng Overlook NM without dodging.

DPS benchmark (28-29k)
{{ youtube(id="u_gXMCOkUh4") }}
QTP Pylon Kiting
{{ youtube(id="1JjqeBQe8jE&t") }}
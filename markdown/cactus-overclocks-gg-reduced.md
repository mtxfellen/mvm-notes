<title>GG Overclocks | fellen's MvM Notes</title>
<link rel="icon" type="image/png" sizes="184x184" href="https://avatars.akamai.steamstatic.com/319d7b492c3a39b04abd80eead00c17590c49e2e_full.jpg">
<style>
/* tf2 colouring */
Pos {color:rgb(153,204,255)}
Neg {color:rgb(255,64,64)}
Neu {color:rgb(235,226,202)}
Nor {color:rgb(178,178,178)}
Uni {color:rgb(255,215,0)}

/* temp theming */
body {
	background-color: #000000;
	color: #d4d4d4;
	font-family: 'Calibri';
	width: 800px;
}

a:link {
  color: #2f81f7;
}

a:visited {
  color: #2f81f7;
}
</style>

<!-- META PROPERTIES -->
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<meta name="author" content="fellen">
<meta property="og:title" content="Galvanized Gauntlet Overclocks">
<meta property="og:type" content="website">
<meta property="og:url" content="https://mtxfellen.github.io">
<meta property="og:site_name" content="fellen's MvM Notes">
<meta property="og:description" content="A list of all Overclock Upgrades in the Galvanized Gauntlet tour.">
<meta property="og:image" content="https://avatars.akamai.steamstatic.com/319d7b492c3a39b04abd80eead00c17590c49e2e_full.jpg">

# Cactus' Overclocks for Galvanized Gauntlet
<p></p>
Overclock Upgrades are an attempt to:

- Increase the usage of weapons considered classically
underpowered,
- Allow alternative playstyles for popular weapons.

The specifics of these upgrades are detailed in this document. A maximum of one overclock is allowed per weapon.

<p></p>
At the time of writing, the Galvanized Gauntlet missions with Overclock Upgrades available are:

- Bronx - Point of Impact (Advanced)
- Goldpit - Race Condition (Advanced)
- Lotus - LED-Motif (Advanced)
- Quetzal - Banana Barricade (Expert)
- Skangus - Metal Scorn (Advanced)
- Steep - Drill Down Disaster (Advanced)
- Waterlogged - Crydodoom (Advanced)

<!-- - Humbridge - Hampton Helix (Advanced) -->

<details>
<summary><font size="+2">Page Contents</font></summary>
<div>
<ul>
  <li><a href="#scout">Scout</a>
  <ul>
    <li><a href="#scout_primary">Primary</a></li>
    <li><a href="#scout_secondary">Secondary</a></li>
    <li><a href="#scout_melee">Melee</a></li>
  </ul>
  </li>
  <li><a href="#soldier">Soldier</a>
  <ul>
    <li><a href="#soldier_primary">Primary</a></li>
    <li><a href="#soldier_secondary">Secondary</a></li>
    <li><a href="#soldier_melee">Melee</a></li>
  </ul>
  </li>
  <li><a href="#pyro">Pyro</a>
  <ul>
    <li><a href="#pyro_primary">Primary</a></li>
    <li><a href="#pyro_secondary">Secondary</a></li>
    <li><a href="#pyro_melee">Melee</a></li>
  </ul>
  </li>
  <li><a href="#demoman">Demoman</a>
  <ul>
    <li><a href="#demoman_primary">Primary</a></li>
    <li><a href="#demoman_secondary">Secondary</a></li>
    <li><a href="#demoman_melee">Melee</a></li>
  </ul>
  </li>
  <li><a href="#heavy">Heavy</a>
  <ul>
    <li><a href="#heavy_primary">Primary</a></li>
    <li><a href="#heavy_secondary">Secondary</a></li>
    <li><a href="#heavy_melee">Melee</a></li>
  </ul>
  </li>
  <li><a href="#engineer">Engineer</a>
  <ul>
    <li><a href="#engineer_primary">Primary</a></li>
    <li><a href="#engineer_secondary">Secondary</a></li>
    <li><a href="#engineer_melee">Melee</a></li>
  </ul>
  </li>
  <li><a href="#medic">Medic</a>
  <ul>
    <li><a href="#medic_primary">Primary</a></li>
    <li><a href="#medic_secondary">Secondary</a></li>
    <li><a href="#medic_melee">Melee</a></li>
  </ul>
  </li>
  <li><a href="#sniper">Sniper</a>
  <ul>
    <li><a href="#sniper_primary">Primary</a></li>
    <li><a href="#sniper_secondary">Secondary</a></li>
    <li><a href="#sniper_melee">Melee</a></li>
  </ul>
  </li>
  <li><a href="#spy">Spy</a>
  <ul>
    <li><a href="#spy_primary">Primary</a></li>
    <li>Secondary</li>
    <li>Melee</li>
    <li><a href="#spy_pda2">PDA2</a></li>
  </ul>
  </li>
</ul>
</div>
</details>

<p></p>
Weapon stats reference

- <Pos>Up to <b>%s1</b>% increased fire rate as health decreases</Pos>
    - Minimum fire rate is retained at 0.9-1x current maximum HP
    - Maximum fire rate is achieved at 0.2x current maximum HP
    - Fire rate is linearly interpolated between 0.2-0.9x current maximum HP
- <Neg>Up to <b>%s1</b>% reduced accuracy as health decreases</Neg>
    - Minimum bullet spread is retained at 0.9-1x current maximum HP
    - Maximum bullet spread is achieved at 0.2x current maximum HP
    - Bullet spread is linearly interpolated between 0.2-0.9x current maximum HP
- <Pos>On weapon hit: One target at a time is Marked-For-Death for 15s</Pos>
    - Like the Fan-o-war, the duration on this is halved when used vs Giants.
- <Neu>Weapon resistances and vulernability</Neu>
  - Like stock weapons that provide these stats, they do not stack additively with resistances. No immortal babies.

## Scout
<h3 id="scout_primary">Primary</h3>

- Unstable Mod: Cycle Overload
  - <Pos>+25% weapon damage</Pos>
  - <Pos>+40% weapon firing speed</Pos>
  - <Neg>-150% weapon reload speed</Neg>
  - <Neg>-100% weapon accuracy</Neg>
  - Available on:
    - <Nor>Scattergun</Nor>
    - <Uni>Back Scatter</Uni>
- Unstable Mod: Vintage Model
  - <Pos>Boost is not reduced on taking damage</Pos>
  - <Pos>+40% weapon accuracy</Pos>
  - <Neg>No double jump on wearer</Neg>
  - <Neg>-10% move speed on wearer</Neg>
  - Available on:
    - <Uni>Baby Face's Blaster</Uni>
- Unstable Mod: Expanded Crit Module
  - <Pos>Weapon always crits from behind</Pos>
  - <Neg>-46% weapon accuracy</Neg>
  - <Neg>-25% weapon reload speed</Neg>
  - Available on:
    - <Uni>Back Scatter</Uni>
- Unstable Mod: Special Delivery
  - <Pos>+25 max health on wearer</Pos>
  - <Pos>+46% weapon reload speed</Pos>
  - <Neg>No double jump on wearer</Neg>
  - <Neg>-10% weapon firing speed</Neg>
  - Available on:
    - <Uni>Shortstop</Uni>
- Unstable Mod:: Slim Slugs
  - <Pos>+10% weapon damage</Pos>
  - <Pos>+20% weapon accuracy</Pos>
  - <Pos>No weapon knockback on target</Pos>
  - <Neg>No weapon knockback on shooter</Pos>
  - <Neg>-15% weapon reload speed</Neg>
  - Available on:
    - <Uni>Force-a-Nature</Uni>
<!--- Unstable Mod: Super Shells
  - <Pos>Hype effect is replaced with mini-crits</Pos>
  - <Neg>-25% weapon reload speed</Neg>
  - <Neg>-50% weapon accuracy</Neg>
  - Available on:
    - <Uni>Soda Popper</Uni>-->

<h3 id="scout_secondary">Secondary</h3>

- Stable Mod: Combo Bullets
  - <Pos>On weapon kill: Wearer gains Crits for 3s.</Pos>
  - <Pos>+25% weapon damage</Pos>
  - Available on:
    - <Nor>Pistol</Nor>
    - <Uni>Pretty Boy's Pocket Pistol</Uni>
    - <Uni>Winger</Uni>
- Unstable Mod: Dairy Mags
  - <Pos>On weapon hit: Apply 2.5s seconds of Mad Milk to target</Pos>
  - <Neg>-75% weapon firing speed</Neg>
  - Available on:
    - <Nor>Pistol</Nor>
    - <Uni>Pretty Boy's Pocket Pistol</Uni>
    - <Uni>Winger</Uni>
- Stable Mod: Battalion's Bonk-up
  - <Neu>Replaces Bonk! Effect with Battalion's Backup effect</Neu>
  - <Pos>Stun and knockback immune during effect</Pos>
  - <Pos>Weapon taunt can be used while airborne</Pos>
  - Available on:
    - <Uni>Bonk! Atomic Punch</Uni>
- Stable Mod: Hot Knife
  - <Pos>On weapon hit: Target is ignited for 7.5s</Pos>
  - <Pos>On weapon hit: One target at a time is Marked-For-Death for 15s</Pos>
  - <Pos>All players connected via Medigun beams are hit by weapon</Pos>
  - <Neg>-50% weapon bleed damage</Neg>
  - Available on:
    - <Uni>Flying Guillotine</Uni>

<h3 id="scout_melee">Melee</h3>

- Unstable Mod: Support Swing
  - <Pos>On weapon hit: One target at a time is Marked-For-Death for 15s</Pos>
  - <Pos>On weapon hit: Apply 6s seconds of Mad Milk to target</Pos>
  - <Neg>-25 max health on wearer</Neg>
  - <Neg>-50% weapon damage</Neg>
  - Available on:
    - <Nor>Bat</Nor>
    - <Uni>Atomizer</Uni>
    - <Uni>Boston Basher</Uni>
    - <Uni>Candy Cane</Uni>
    - <Uni>Holy Mackerel</Uni>
    - <Uni>Sandman</Uni>
    - <Uni>Sun-on-a-Stick</Uni>
    - <Uni>Wrap Assassin</Uni>
- Unstable Mod: Craftsman's Bat
  - <Pos>+15 max health on wearer</Pos>
  - <Pos>On weapon hit: Bleed target for 5s</Pos>
  - <Pos>+300% weapon bleeding damage</Pos>
  - <Neg>-35% swing speed</Pos>
  - Available on:
    - <Uni>Boston Basher</Uni>
    - <Uni>Sandman</Uni>
- Unstable Mod: Sugar Shock
  - <Pos>On weapon hit: One target at a time is Marked-For-Death for 15s</Pos>
  - <Pos>Wearer blast damage vulnerability removed</Pos>
  - <Pos>On weapon hit: Gain a speed boost for 5s</Pos>
  - <Neg>-15 max health on wearer</Neg>
  - Available on:
    - <Uni>Candy Cane</Uni>
- Unstable Mod: Soul Scorcher
  - <Pos>+600% base weapon damage vs burning players</Pos>
  - <Pos>All players connected via Medigun beams are hit by weapon</Pos>
  - <Neg>90% damage penalty vs non-burning players</Neg>
  - Available on:
    - <Uni>Sun-on-a-Stick</Uni>
- Unstable Mod: Heavy Material
  - <Neu>When weapon is active:</Neu>
    - <Pos>-30% damage from ranged sources</Pos>
    - <Neg>-10% move speed</Neg>
  - Available on:
      - <Uni>Atomizer</Uni>

## Soldier
<h3 id="soldier_primary">Primary</h3>

- Unstable Mod: RPG Module
  - <Pos>+25% weapon damage</Pos>
  - <Pos>+35% weapon blast radius</Pos>
  - <Pos>Weapon projectiles cannot be reflected or deflected</Pos>
  - <Neg>Weapon Clip Size cannot be upgraded</Neg>
  - <Neg>Rockets now fire in an arc</Neg>
  - <Neg>-75% weapon clip size</Neg>
  - <Neg>-75% weapon reload speed</Neg>
  - <Neg>-20% weapon firing speed</Neg>
  - Available on:
    - <Nor>Rocket Launcher</Nor>
    - <Uni>Original</Uni>
- Unstable Mod: Extra Gunpowder
  - <Pos>+15% weapon damage</Pos>
  - <Pos>+25% weapon damage to tanks</Pos>
  - <Pos>Weapon projectiles cannot be reflected or deflected</Pos>
  - <Neg>-20% weapon blast radius</Neg>
  - <Neg>-25% weapon clip size</Neg>
  - Available on:
    - <Uni>Direct Hit</Uni>
- Unstable Mod: Bionic Box
  - <Pos>On weapon hit: +40 health per enemy hit</Pos>
  - <Pos>+99% firing speed</Pos>
  - <Pos>+10% weapon reload speed</Pos>
  - <Pos>+100% primary reserve ammo</Pos>
  - <Neg>-60% weapon damage</Neg>
  - <Neg>Weapon cannot fire until all rockets are loaded</Neg>
  - <Neg>+3 degrees random weapon projectile deviation</Neg>
  - <Neg>-25% weapon projectile speed</Neg>
  - Available on:
    - <Uni>Black Box</Uni>
- Unstable Mod: Tank Buster
  - <Pos>Heal-on-hit stacks vs multiple enemies</Pos>
  - <Pos>+20% weapon damage vs tanks</Pos>
  - <Neg>-25% weapon projectile speed</Neg>
  - Available on:
    - <Uni>Black Box</Uni>
- Unstable Mod: Jump Module
  - <Pos>+40% weapon firing speed</Pos>
  - <Pos>+35% weapon blast radius</Pos>
  - <Pos>+50% primary reserve ammo</Pos>
  - <Neg>-15% weapon damage</Neg>
  - Available on:
    - <Uni>Liberty Launcher</Uni>
- Unstable Mod: Smart Rockets
  - <Pos>0.1x weapon firing delay while blast jumping</Pos>
  - <Neu>Rockets home to crosshair position</Neu>
  - <Neg>-50% weapon clip size</Neg>
  - <Neg>-15% weapon damage</Neg>
  - <Neg>+25% self-damage from blast jumping</Neg>
  - <Neg>-35% weapon projectile speed</Neg>
  - <Neg>Rockets detonate after 2.5s</Neg>
  - Available on:
    - <Uni>Air Strike</Uni>

<h3 id="soldier_secondary">Secondary</h3>

- Stable Mod: Debuff Rounds
  - <Pos>On weapon hit: One target at a time is Marked-For-Death for 15s</Pos>
  - Available on:
    - <Nor>Shotgun</Nor>
    - <Uni>Panic Attack</Uni>
    - <Uni>Reserve Shooter</Uni>
- Unstable Mod: Air-raid rounds
  - <Pos>Weapon always crits while blast jumping</Pos>
  - <Pos>0.5x weapon firing delay while blast jumping</Pos>
  - <Pos>+50% weapon accuracy</Pos>
  - <Pos>Provides the B.A.S.E. Jumper to wearer</Pos>
  - <Neg>-50% weapon firing speed</Neg>
  - Available on:
    - <Uni>Reserve Shooter</Uni>
- Stable Mod: Titanium Soles
  - <Pos>+200% credit collection radius on wearer</Pos>
  - <Pos>Wearer never takes falling damage</Pos>
  - <Pos>+25% primary reserve ammo</Pos>
  - <Neg>No weapon stomp damage</Neg>
  - Available on:
    - <Uni>Gunboats</Uni>
    - <Uni>Mantreads</Uni>
- Unstable Mod: Slim Rockets
  - <Pos>+15% reload speed on wearer</Pos>
  - <Neg>-50% primary reserve ammo</Neg>
  - <Neg>-50% secondary reserve ammo</Neg>
  - Available on:
    - <Uni>B.A.S.E. Jumper</Uni>
    - <Uni>Gunboats</Uni>
- Unstable Mod: Heavy Duty Boots
  - <Pos>+175 stomp damage</Pos>
  - <Pos>+10% move speed on wearer<Pos>
  - Available on:
    - <Uni>Mantreads</Uni>
- Stable Mod: Improved Parachute
  - <Pos>200% increased air control on wearer</Pos>
  - <Pos>Parachute re-deploy allowed</Pos>
  - <Pos>+50% primary reserve ammo</Pos>
  - Available on:
    - <Uni>B.A.S.E. Jumper</Uni>
- Stable Mod: Combo Slugs
  - <Pos>+35% weapon damage</Pos>
  - <Pos>On weapon kill: Wearer gains Mini-crits for 5s.</Pos>
  - Available on:
    - <Uni>Panic Attack</Uni>
- Unstable Mod: Prototype Panic
  - <Pos>+40% weapon damage</Pos>
  - <Pos>+34% weapon reload speed</Pos>
  - <Pos>Up to +50% weapon firing speed as health decreases</Pos>
  - <Neg>Fires -50% bullets per shot</Neg>
  - <Neg>-25% weapon clip size</Neg>
  - <Neg>Hold fire to load up to 4 shells</Neg>
  - <Neg>Auto-fires full clip once released</Neg>
  - Available on:
    - <Uni>Panic Attack</Uni>
<!-- - Unstable Mod: Condensed Core
  - <Pos>+900% weapon damage</Pos>
  - <Pos>Weapon projectiles can headshot</Pos>
  - <Pos>Weapon projectiles bounce off walls, retaining 80% of speed after each bounce</Pos>
  - <Neg>Weapon projectiles cannot hit the same target multiple times</Neg>
  - <Neg>Clip Size cannot be upgraded</Neg>
  - <Neg>Weapon projectiles now fire in an arc</Neg>
  - <Neg>Weapon projectiles expire after 2s</Neg>
  - Available on:
    - <Uni>Righteous Bison</Uni>-->
- Unstable Mod: Burst Lens
  - <Pos>Weapon fires four rounds at once</Pos>
  - <Pos>Weapon reloads four rounds at once</Pos>
  - <Pos>+50% weapon projectile speed</Pos>
  - <Pos>Projectile penetrates teammates</Pos>
  - <Neg>Projectiles expire after 0.3s</Neg>
  - <Neg>-35% weapon damage</Neg>
  - <Neg>-50% weapon reload speed</Neg>
  - <Neg>Reload Speed cannot be upgraded</Neg>
  - Available on:
    - <Uni>Righteous Bison</Uni>

<h3 id="soldier_melee">Melee</h3>

- Unstable Mod: Support Beacon
  - <Pos>+100% buff range while active</Pos>
  - <Pos>+25% weapon damage</Pos>
  - <Neg>On miss: Hit yourself, idiot.</Neg>
  - Available on:
    - <Nor>Shovel</Nor>
    - <Uni>Disciplinary Action</Uni>
    - <Uni>Equalizer</Uni>
    - <Uni>Escape Plan</Uni>
    - <Uni>Pain Train</Uni>
- Unstable Mod: Magnetic Spike
  - <Pos>+150% melee range</Pos>
  - <Pos>+100% credit collection radius on wearer</Pos>
  - <Pos>+35% weapon damage</Pos>
  - <Neg>+10% bullet damage taken</Neg>
  - Available on:
    - <Uni>Pain Train</Uni>
- Unstable Mod: Titanic Toppler
  - <Pos>All players connected via Medigun beams are hit by weapon</Pos>
  - <Pos>+100% weapon damage vs Giants</Pos>
  - <Pos>+50% melee range</Pos>
  - <Neg>-15% weapon attack speed</Neg>
  - Available on:
    - <Uni>Market Gardener</Uni>
- Stable Mod: Combo Swing
  - <Pos>On weapon kill: Wearer gains Crits for 4s.</Pos>
  - <Pos>+100% melee range</Pos>
  - Available on:
    - <Uni>Market Gardener</Uni>
- Stable Mod: Survival Training
  - <Pos>+25% weapon damage</Pos>
  - <Pos>-35% damage taken from ranged sources while active</Pos>
  - Available on:
    - <Uni>Equalizer</Uni>
- Unstable Mod: Samurai Spirit
  - <Pos>+20% weapon attack speed
  - <Pos>On weapon kill: Wearer gains Mini-crits for 5s.</Pos>
  - <Neu>When weapon is active:</Neu>
    - <Pos>+10% move speed</Pos>
    - <Neg>+15% damage vulnerability</Neg>
  - Available on:
    - <Uni>Half-Zatoichi</Uni>

## Pyro
<h3 id="pyro_primary">Primary</h3>

- Unstable Mod: Caustic Fumes
  - <Pos>+10% weapon damage</Pos>
  - <Pos>Attacks with this weapon pierce damage resistance effects and bonuses</Pos>
  - <Pos>On weapon hit: Apply Gas to target</Pos>
  - <Neg>Airblast no longer pushes back players</Neg>
  - Available on:
    - <Nor>Flamethrower</Nor>
- Unstable Mod: Acidic Compound
  - <Pos>+15% damage vs Tanks</Pos>
  - <Neg>No compression blast</Neg>
  - Available on:
    - <Uni>Backburner</Uni>
- Unstable Mod: Leech Valve
  - <Pos>On weapon hit: Gain up to +15 health per enemy hit</Pos>
  - <Neg>-10% weapon damage</Neg>
  - Available on:
    - <Uni>Dragon's Fury</Uni>
- Unstable Mod: Gas Jockey
  - <Pos>+50% re-pressurization rate</Pos>
  - <Pos>Attacks with this weapon pierce damage resistance effects and bonuses</Pos>
  - <Pos>10% faster move speed on wearer</Pos>
  - <Neg>Airblast no longer pushes back players</Neg>
  - <Neg>-10% weapon damage</Neg>
  - Available on:
    - <Uni>Degreaser</Uni>

<h3 id="pyro_secondary">Secondary</h3>

- Stable Mod: Titanium Soles
  - <Pos>+200% credit collection radius on wearer</Pos>
  - <Pos>Wearer never takes falling damage</Pos>
  - <Pos>+25% primary reserve ammo</Pos>
  - Available on:
    - <Uni>Thermal Thruster</Uni>
- Unstable Mod: Heavy Duty Boots
  - <Pos>+175 stomp damage</Pos>
  - <Pos>+10% move speed on wearer<Pos>
  - Available on:
    - <Uni>Thermal Thruster</Uni>
- Stable Mod: Combo Slugs
  - <Pos>+25% weapon damage</Pos>
  - <Pos>On weapon kill: Wearer gains Mini-crits for 5s.</Pos>
  - Available on:
    - <Uni>Panic Attack</Uni>
- Unstable Mod: Prototype Panic
  - <Pos>+40% weapon damage</Pos>
  - <Pos>+34% weapon reload speed</Pos>
  - <Pos>Up to +50% weapon firing speed as health decreases</Pos>
  - <Neg>Fires -50% bullets per shot</Neg>
  - <Neg>-25% weapon clip size</Neg>
  - <Neg>Hold fire to load up to 4 shells</Neg>
  - <Neg>Auto-fires full clip once released</Neg>
  - Available on:
    - <Uni>Panic Attack</Uni>
- Unstable Mod: Volcanic Compound
  - <Pos>+75% weapon damage</Pos>
  - <Neg>-35% weapon projectile speed</Neg>
  - Available on:
    - <Uni>Detonator</Uni>
    - <Uni>Flare Gun</Uni>
    - <Uni>Scorch Shot</Uni>
- Unstable Mod: Molten Core
  - <Pos>+200% weapon afterburn tick rate</Pos>
  - <Pos>On weapon hit: Bleed target for 3s</Pos>
  - <Pos>+300% weapon bleed damage</Pos>
  - <Neg>-50% weapon projectile speed</Neg>
  - Available on:
    - <Uni>Manmelter</Uni>
- Unstable Mod: Trench Gun
  - <Pos>Fires +20% bullets per shot</Pos>
  - <Pos>On weapon hit: target is ignited for 7.5s</Pos>
  - <Pos>+150% weapon afterburn tick rate</Pos>
  - <Neg>-35% weapon accuracy</Neg>
  - Available on:
    - <Nor>Shotgun</Nor>
    - <Uni>Reserve Shooter</Uni>
- Unstable Mod: Australian Gas
  - <Pos>Weapon now coats players in Jarate</Pos>
  - <Neg>-75% weapon effect duration</Neg>
  - Available on:
    - <Uni>Gas Passer</Uni>

<h3 id="pyro_melee">Melee</h3>

- Unstable Mod: Heavy Mallet
  - <Neg>-25% weapon damage vs players</Neg>
  - <Neu>When weapon is active:</Neu>
    - <Pos>-35% bullet damage taken</Pos>
    - <Pos>-90% push force taken from damage</Pos>
  - Available on:
    - <Uni>Homewrecker</Uni>
- Unstable Mod: Gordbort Capacitor
  - <Pos>All players connected via Medigun beams are hit by weapon</Pos>
  - <Neg>-25% weapon attack speed</Neg>
  - Available on:
    - <Uni>Neon Annihilator</Uni>
- Unstable Mod: Armor Breaking
  - <Pos>+20% weapon damage</Pos>
  - <Pos>+35% weapon damage vs Giants</Pos>
  - <Pos>+35% weapon damage vs Tanks</Pos>
  - <Neg>-20% weapon attack speed</Neg>
  - Available on:
    - <Nor>Fire Axe</Nor>
    - <Uni>Axtinguisher</Uni>
    - <Uni>Homewrecker</Uni>
    - <Uni>Powerjack</Uni>
    - <Uni>Sharpened Volcano Fragment</Uni>
- Unstable Mod: Serrated Axe
  - <Pos>Weapon always crits burning players</Pos>
  - <Pos>Weapon does not extinguish burning targets</Pos>
  - <Neg>-75% weapon damage vs non-burning players</Neg>
  - Available on:
    - <Uni>Axtinguisher</Uni>
- Unstable Mod: Draining Coils
  - <Pos>On weapon hit: Victim loses up to 15% Medigun charge</Pos>
  - <Neg>-15 max health on wearer</Neg>
  - Available on:
    - <Uni>Third Degree</Uni>
- Unstable Mod: Premium Rake
  - <Pos>Weapon attacks all enemies in range</Pos>
  - <Pos>+25% health from healers</Pos>
  - <Neg>-50% health from packs</Neg>
  - Available on:
    - <Uni>Back Scratcher</Uni>
- Unstable Mod: Hell-Forged Heal
  - <Pos>On weapon hit: Gain up to +25 health</Pos>
  - <Pos>+150% weapon afterburn tick rate</Pos>
  - <Neg>-20% weapon damage</Neg>
  - Available on:
    - <Uni>Sharpened Volcano Fragment</Uni>
- Stable Mod: Team Bonding
  - <Pos>+70% weapon melee range</Pos>
  - <Pos>+55% weapon swing radius</Pos>
  - <Pos>+80% weapon damage</Pos>
  - <Pos>On weapon teammate hit: Boosts both players' speed for 5s</Pos>
  - Available on:
    - <Uni>Hot Hand</Uni>

## Demoman
<h3 id="demoman_primary">Primary</h3>

- Unstable Mod: Slim Rockets
  - <Pos>+15% reload speed on wearer</Pos>
  - <Neg>-50% primary reserve ammo</Neg>
  - <Neg>-50% secondary reserve ammo</Neg>
  - Available on:
    - <Uni>B.A.S.E. Jumper</Uni>
- Stable Mod: Improved Parachute
  - <Pos>200% increased air control on wearer</Pos>
  - <Pos>Parachute re-deploy allowed</Pos>
  - Available on:
    - <Uni>B.A.S.E. Jumper</Uni>
- Unstable Mod: Mortar Mode
  - <Pos>+30% weapon firing speed</Pos>
  - <Pos>+35% weapon blast radius</Pos>
  - <Neg>+3 degrees random weapon projectile deviation</Neg>
  - <Neg>Hold fire to load up to 4 grenades</Neg>
  - <Neg>Auto-fires full clip once released</Neg>
  - <Neu>Overloading the chamber will cause a misfire</Neu>
  - Available on:
    - <Nor>Grenade Launcher</Nor>
    - <Uni>Iron Bomber</Uni>
- Unstable Mod: Burst Chamber
  - <Pos>Weapon fires a bonus pipebomb per round</Pos>
  - <Pos>Launched bombs do not shatter on surfaces</Pos>
  - <Neg>-35% weapon damage</Neg>
  - <Neg>-50% weapon blast radius</Neg>
  - <Neg>-50% weapon damage on contact with surfaces</Neg>
  - Available on:
    - <Uni>Loch-n-Load</Uni>
- Unstable Mod: Blunderbuss
  - <Pos>On weapon hit: Refill 75% of your shield charge meter</Pos>
  - <Pos>On weapon kill: Gain all banner effects for 4s</Pos>
  - <Pos>Cannonballs explode on impact</Pos>
  - <Pos>+20% weapon damage</Pos>
  - <Pos>-75% self damage taken from blast jumping</Pos>
  - <Neg>-50% weapon clip size</Neg>
  - Available on:
    - <Uni>Loose Cannon</Uni>
- Unstable Mod: Cash Magnet
  - <Pos>+200% credit collection radius on wearer</Pos>
  - <Neg>-75% reload speed on wearer</Neg>
  - <Neg>-25 max health on wearer</Neg>
  - <Neg>-50% secondary reserve ammo</Neg>
  - Available on:
    - <Uni>Ali Baba's Wee Booties</Uni>

<h3 id="demoman_secondary">Secondary</h3>

- Stable Mod: Titanium Soles
  - <Pos>+200% credit collection radius on wearer</Pos>
  - <Pos>Wearer never takes falling damage</Pos>
  - <Pos>+25% primary reserve ammo</Pos>
  - Available on:
    - <Uni>Sticky Jumper</Uni>
- Unstable Mod: Extra Adhesive
  - <Pos>-0.1s weapon sticky arm time</Pos>
  - <Pos>Stickybombs stick to enemies</Pos>
  - <Neg>-2 max stickybombs out</Neg>
  - Available on:
    - <Nor>Stickybomb Launcher</Nor>
- Unstable Mod: Overloaded Drum
  - <Pos>+2 max stickybombs out</Pos>
  - <Pos>+35% weapon firing speed</Pos>
  - <Pos>-0.4s weapon sticky arm time</Pos>
  - <Pos>Stickybombs stick to enemies</Pos>
  - <Neg>+6 degrees random projectile deviation</Neg>
  - <Neg>Hold fire to load up to 8 bombs</Neg>
  - <Neg>Auto-fires full clip once released</Neg>
  - <Neg>-1000% max sticky charge time</Neg>
  - <Neu>Overloading the chamber will cause a misfire</Neu>
  - Available on:
    - <Uni>Scottish Resistance</Uni>
- Unstable Mod: Prototype Sensor
  - <Pos>+25% weapon clip size</Pos>
  - <Pos>+20% weapon damage at full charge</Pos>
  - <Pos>-15% max sticky charge time</Pos>
  - <Neg>Stickybombs fizzle 1.5s after landing</Neg>
  - <Neu>Projectile model appears at 2x scale</Neu>
  - Available on:
    - <Uni>Quickiebomb Launcher</Uni>
- Unstable Mod: Clash Combo
  - <Pos>On shield kill: Wearer gains 4s of crits</Pos>
  - <Neg>-70% reload speed on wearer</Neg>
  - Available on:
    - <Uni>Chargin' Targe</Uni>
    - <Uni>Splendid Screen</Uni>
    - <Uni>Tide Turner</Uni>
- Unstable Mod: Pocket Incinerator
  - <Pos>+40 health from collected credits</Pos>
  - <Neg>-75% reload speed on wearer</Neg>
  - <Neg>-25% fire damage resistance on wearer</Neg>
  - <Neg>-15% blast damage resistance on wearer</Neg>
  - Available on:
    - <Uni>Chargin' Targe</Uni>
- Unstable Mod: Pocket Incinerator
  - As above, but instead with: 
    - <Neg>-20% fire damage resistance on wearer</Neg>
    - <Neg>-20% blast damage resistance on wearer</Neg>
  - Available on:
    - <Uni>Splendid Screen</Uni>
- Unstable Mod: Pocket Incinerator
  - As above, but instead with: 
    - <Neg>-15% fire damage resistance on wearer</Neg>
    - <Neg>-15% blast damage resistance on wearer</Neg>
  - Available on:
    - <Uni>Tide Turner</Uni>

<h3 id="demoman_melee">Melee</h3>

- Unstable Mod: Magnetic Spike
  - <Pos>+150% melee range</Pos>
  - <Pos>+100% credit collection radius on wearer</Pos>
  - <Pos>+35% weapon damage</Pos>
  - <Neg>+10% bullet damage taken</Neg>
  - Available on:
    - <Uni>Pain Train</Uni>
- Unstable Mod: Gardener Module
  - <Pos>Weapon deals crits while blast jumping</Pos>
  - <Pos>+25% melee range</Pos>
  - <Neg>-10% weapon attack speed</Neg>
  - Available on:
    - <Nor>Bottle</Nor>
- Unstable Mod: Cushioned Explosive
  - <Pos>No weapon self-knockback</Pos>
  - <Neg>+50% weapon self damage</Neg>
  - Available on:
    - <Uni>Ullapool Caber</Uni>
- Unstable Mod: Scottish Steel
  - <Neu>When weapon is active:</Neu>
    - <Pos>-15% damage vulnerability</Pos>
    - <Pos>+400% to turning control when charging</Pos>
    - <Pos>+1.5s to charge duration</Pos>
  - <Pos>Weapon always crits from behind</Pos>
  - <Neg>-25% weapon attack speed</Neg>
  - Available on:
    - <Uni>Claidheamh Mòr</Uni>
- Unstable Mod: Shield Slam
  - <Pos>+200% shield charge impact damage</Pos>
  - <Neg>-20% weapon attaack speed</Neg>
  - Available on:
    - <Uni>Persian Persuader</Uni>

## Heavy
<h3 id="heavy_primary">Primary</h3>

<!-- - Unstable Module: Hurricane Module
  - <Pos>+275% weapon damage</Pos>
  - <Pos>+350% weapon damage vs Tanks</Pos>
  - <Pos>+35% weapon damage vs Giants</Pos>
  - <Pos>Knockback Rage now instead applies Rocket Specialist</Pos>
  - <Pos>Can be holstered while spinning</Pos>
  - <Neu>Fires rockets instead of bullets</Neu>
    - <Pos>Rockets fire from the center like the Original</Pos>
    - <Neu>Rockets use the Flare Gun trail</Neu>
    - <Neu>Rockets use the model associated with the Rescue Ranger</Neu>
  - <Neu>Rockets home to crosshair position</Neu>
  - <Neg>-330% weapon firing speed</Neg>
  - <Neg>Projectiles detonate after 2.8s</Neg>
  - <Neg>Cannot be revved</Neg>
  - <Neg>-75% primary ammo</Neg>
  - <Neg>No primary ammo from dispensers when active</NEg>
  - <Neg>Mini-crits whenever it would normally crit</Neg>
  - <Neg>Weapon damage does not fill the crit bucket</Neg>
  - Available on:
    - <Nor>Minigun</Nor>-->
- Unstable Mod: Defense Framework
  - <Pos>Can be holstered while spinning</Pos>
  - <Pos>+30% damage resistance when below 50% health and spun up</Pos>
  - <Pos>50% critical damage resistance on wearer</Pos>
  - <Pos>No spin up time penalty</Pos>
  - <Neg>-100% maximum overheal while active</Neg>
  - <Neg>Cannot move while weapon is deployed</Neg>
  - Available on:
    - <Uni>Brass Beast</Uni>
- Unstable Mod: Leadstorm
  - <Pos>+20% weapon damage</Pos>
  - <Pos>-30% to spin up time</Pos>
  - <Pos>Can be holstered while spinning</Pos>
  - <Neg>Cannot move while weapon is deployed</Neg>
  - <Neg>No spun up damage resistance</Neg>
  - Available on:
    - <Uni>Natascha</Uni>
- Unstable Mod: Optimized Barrel
  - <Pos>No movement penalty when spun up</Pos>
  - <Pos>Knockback Rage now instead causes attacks to pierce damage resistance effects and bonuses</Pos>
  - <Pos>Can be holstered while spinning</Pos>
  - <Neg>-50% primary ammo capcity</Neg>
  - Available on:
    - <Uni>Tomislav</Uni>
- Unstable Mod: Bigger Bullets
  - <Pos>+10% weapon damage</Pos>
  - <Pos>Knockback Rage now instead applies afterburn</Pos>
  - <Neg>Consumes an additional 3 ammo per second while spun up</Neg>
  - Available on:
    - <Uni>Huo-Long Heater</Uni>

<h3 id="heavy_secondary">Secondary</h3>

- Stable Mod: Combo Slugs
  - <Pos>+25% weapon damage</Pos>
  - <Pos>On weapon kill: Wearer gains Mini-crits for 5s.</Pos>
  - Available on:
    - <Nor>Shotgun</Nor>
    - <Uni>Family Business</Uni>
    - <Uni>Panic Attack</Uni>
- Unstable Mod: Prototype Panic
  - <Pos>+40% weapon damage</Pos>
  - <Pos>+34% weapon reload speed</Pos>
  - <Pos>Up to +50% weapon firing speed as health decreases</Pos>
  - <Neg>Fires -50% bullets per shot</Neg>
  - <Neg>-25% weapon clip size</Neg>
  - <Neg>Hold fire to load up to 4 shells</Neg>
  - <Neg>Auto-fires full clip once released</Neg>
  - Available on:
    - <Uni>Panic Attack</Uni>
- Unstable Mod: Defensive Blast
  - <Pos>75% of weapon damage is healed as life</Pos>
  - <Pos>Weapon bullets destroy projectiles in-flight</Pos>
  - <Neg>-10% weapon damage</Neg>
  - Available on:
    - <Uni>Family Business</Uni>
- Stable Mod: Mannly Meal
  - <Pos>+175% to gesture speed on wearer</Pos>
  - <Pos>Consuming also grants Concheror effect</Pos>
  - Available on:
    - <Uni>Buffalo Steak Sandvich</Uni>

<h3 id="heavy_melee">Melee</h3>

- Stable Mod: More Storage Space
  - <Pos>+25% primary ammo capacity</Pos>
  - <Pos>+35% weapon switch speed on wearer</Pos>
  - Available on:
    - <Nor>Fists</Nor>
- Unstable Mod: Improved Robo Gru
  - <Neu>When weapon is active:</Neu>
    - <Pos>No max health drain when active</Pos>
    - <Pos>+5% faster move speed</Pos>
    - <Neg>You are Marked-For-Death, and for short period after switching weapons</Neg>
  - Available on:
    - <Uni>Gloves of Running Urgently</Uni>
- Unstable Mod: Fuzzier Wool
  - <Pos>Crits whenever it would normally mini-crit</Pos>
  - <Neg>-15% weapon attack speed</Neg>
  - Available on:
    - <Uni>Holiday Punch</Uni>
- Unstable Mod: Brute Bracers
  - <Pos>+30% weapon damage</Pos>
  - <Pos>Crits whenever it would normally mini-crit</Pos>
  - <Neu>When weapon is active:</Neu>
    - <Pos>No max health drain</Pos>
    - <Neg>+15% damage vulnerability</Neg>
  - Available on:
    - <Uni>Eviction Notice</Uni>
- Unstable Mod: Warrior's Code
  - <Pos>No damage vulnerability</Pos>
  - <Pos>Crits whenever it would normally mini-crit</Pos>
  - <Neg>-30% weapon attack speed</Neg>
  - <Neg>Honorbound: Once drawn sheathing deals 50 damage to yourself unless it kills.</Neg>
  - Available on:
    - <Uni>Warrior's Spirit</Uni>
- Unstable Mod: Heavy Duty Steel
  - <Pos>+40% ranged damage resistance</Pos>
  - <Neg>+100% increased melee damage vulnerability</Neg>
  - <Neg>-60% maximum overheal</Neg>

## Engineer
<h3 id="engineer_primary">Primary</h3>

- Stable Mod: Combo Slugs
  - <Pos>+25% weapon damage</Pos>
  - <Pos>On weapon kill: Wearer gains Mini-crits for 5s.</Pos>
  - Available on:
    - <Nor>Shotgun</Nor>
    - <Uni>Panic Attack</Uni>
- Unstable Mod: Prototype Panic
  - <Pos>+40% weapon damage</Pos>
  - <Pos>+34% weapon reload speed</Pos>
  - <Pos>Up to +50% weapon firing speed as health decreases</Pos>
  - <Neg>Fires -50% bullets per shot</Neg>
  - <Neg>-25% weapon clip size</Neg>
  - <Neg>Hold fire to load up to 4 shells</Neg>
  - <Neg>Auto-fires full clip once released</Neg>
  - Available on:
    - <Uni>Panic Attack</Uni>
- Unstable Mod: Sentry Companion A.I
  - <Pos>+30% sentry range</Pos>
  - <Pos>+30% weapon damage to your sentry's target</Pos>
  - <Neg>Per Shot: -25 metal</Neg>
  - Available on:
    - <Uni>Widowmaker</Uni>
- Unstable Mod: Custom Engineered Shotgun
  - <Pos>Alt-Fire: Use 150 metal to pick up your targeted building from long range</Pos>
  - <Neg>Self mark-for-death when hauling buildings</Neg>
  - Available on:
    - <Nor>Shotgun</Nor>
    - <Uni>Frontier Justice</Uni>
    - <Uni>Widowmaker</Uni>
- Unstable Mod: Improved Transistors
  - <Pos>Alt-Fire: Use 100 metal to pick up your targeted building from long range</Pos>
  - <Pos>+100% weapon damage</Pos>
  - <Pos>+100% weapon projectile speed</Pos>
  - <Pos>On weapon hit: Bleed for 1s</Pos>
  - <Pos>Projectile penetrates teammates</Pos>
  - <Pos>Projectile penetrates enemy targets</Pos>
  - Available on:
    - <Uni>Pomson 6000</Uni>
- Unstable Mod: Burst Lens
  - <Pos>Weapon fires four rounds at once</Pos>
  - <Pos>Weapon reloads four rounds at once</Pos>
  - <Pos>+50% weapon projectile speed</Pos>
  - <Pos>Projectile penetrates teammates</Pos>
  - <Neg>Projectiles expire after 0.3s</Neg>
  - <Neg>-35% weapon damage</Neg>
  - <Neg>-50% weapon reload speed</Neg>
  - <Neg>Reload Speed cannot be upgraded</Neg>
  - Available on:
    - <Uni>Pomson 6000</Uni>
- Unstable Mod: Compact Sensor
  - <Pos>Long-range haul cost reduced to 50 metal</Pos>
  - <Neg>-25% max metal on wearer</Neg>
  - <Neg>-16% weapon clip size</Neg>
  - Available on:
    - <Uni>Rescue Ranger</Uni>

<h3 id="engineer_secondary">Secondary</h3>

- Stable Mod: Sentry Companion
  - <Pos>+50% max building health</Pos>
  - <Pos>Teleporters can be used in both directions</Pos>
  - Available on:
    - <Nor>Pistol</Nor>
- Stable Mod: Combat Sensor
  - <Pos>+50% damage bonus to your sentry's target</Pos>
  - <Pos>On Kill: Gain Mini-crits for 6 seconds.</Pos>
  - <Pos>-25% building cost</Pos>
  - Available on:
    - <Nor>Pistol</Nor>
- Unstable Mod: Sentry Jumper
  - <Pos>-95% self-damage taken from blast jumping</Pos>
  - <Pos>Wearer never takes falling damage</Pos>
  - <Neg>-10% max metal on wearer</Neg>
  - Available on:
    - <Nor>Wrangler</Nor>
- Unstable Mod: Overclocked Circuit
  - <Pos>Primary fire uses explosive bullets</Pos>
  - <Pos>+500% weapon damage</Pos>
  - <Pos>On weapon hit: 10 damage dealt is returned as metal</Pos>
  - <Pos>Weapon range increased to 750HU</Pos>
  - <Pos>Weapon bullets destroy projectiles in-flight</Pos>
  - <Neg>Secondary fire disabled</Neg>
  - <Neg>-250% weapon firing speed</Neg>
  - <Neg>-35% weapon damage vs players</Neg>
  - <Neg>+25% to self blast damage on wearer</Neg>
  - Available on:
    - <Uni>Short Circuit</Uni>

<h3 id="engineer_melee">Melee</h3>

- Stable Mod: Mobile Processors
  - <Pos>Grants an additional Disposable Sentry</Pos>
  - <Pos>+200% to construction hit boost speed</Pos>
  - <Pos>+200% to dispenser health, ammo and metal output rate</Pos>
  - <Pos>+50% sentry range</Pos>
  - <Pos>Teleporter recharges 50% faster</Pos>
  - <Pos>+50% weapon damage</Pos>
  - Available on:
    - <Uni>Gunslinger</Uni>
- Unstable Mod: Battle Module
  - <Pos>+200% weapon bleeding damage</Pos>
  - <Pos>No fire damage vulnerability</Pos>
  - <Neu>When weapon is active:</Neu>
    - <Pos>+20% sentry gun damage</Pos>
    - <Pos>+50% sentry range</Pos>
    - <Neg>-50% repair rate</Neg>
    - <Neg>+20% damage vulnerability</Neg>
  - Available on:
    - <Uni>Southern Hospitality</Uni>


## Medic
<h3 id="medic_primary">Primary</h3>

- Unstable Mod: Support Bolts
  - <Pos>On weapon hit: Apply 4s seconds of Mad Milk to target</Pos>
  - <Neg>-75% weapon reload speed</Neg>
  - <Neg>-50% weapon damage</Neg>
  - Available on:
    - <Uni>Crusader's Crossbow</Uni>
- Unstable Mod: Burst Reload
  - <Pos>Weapon reloads its entire clip at once</Pos>
  - <Neg>-50% weapon reload speed</Neg>
  - <Neg>-20% weapon damage</Neg>
  - <Neg>Reload Speed cannot be upgraded</Neg>
  - Available on:
    - <Uni>Crusader's Crossbow</Uni>
- Unstable Mod: Biohazard Needle
  - <Pos>On weapon hit: Apply 3s seconds of Jarate to target</Pos>
  - <Neg>-35% weapon reload speed</Neg>
  - <Neg>-75% weapon clip size</Neg>
  - <Neg>-75% weapon damage</Neg>
  - Available on:
    - <Nor>Syringe Gun</Nor>
    - <Uni>Blutsauger</Uni>
    - <Uni>Overdose</Uni>

<h3 id="medic_secondary">Secondary</h3>

- Unstable Mod: Broken Shield Lens
  - <Pos>+15 max health on wearer</Pos>
  - <Pos>+20% weapon heal rate</Pos>
  - <Pos>+5% ÜberCharge rate on Overhealed patients</Pos>
  - <Neg>-100% Projectile Shield damage</Neg>
  - <Neg>-65% Projectile Shield duration</Neg>
  - Available on:
    - <Nor>Medi Gun</Nor>
    - <Uni>Kritzkrieg</Uni>
- Unstable Mod: Prototype Module
  - <Pos>+50% weapon heal rate</Pos>
  - <Pos>Heal buildings at a rate of 40%/s</Pos>
  - <Neg>-50% maximum overheal</Neg>
  - <Neg>-20% ÜberCharge rate on Overhealed patients</Neg>
  - <Neg>-20% overheal duration</Neg>
  - Available on:
    - <Uni>Quick-Fix</Uni>

<h3 id="medic_melee">Melee</h3>

- Stable Mod: Battery Leech
  - <Pos>On weapon hit: 15% ÜberCharge added</Pos>
  - Available on:
    - <Nor>Bonesaw</Nor>
    - <Uni>Vita-Saw</Uni>
    - <Uni>Solemn Vow</Uni>
- Stable Mod: Mark Module
  - <Pos>On weapon hit: One target at a time is Marked-For-Death for 15s</Pos>
  - Available on:
    - <Nor>Bonesaw</Nor>
    - <Uni>Solemn Vow</Uni>
- Unstable Mod: Protection Mode
  - <Neu>When weapon is active:</Neu>
    - <Pos>+3 health regenerated per second</Pos>
    - <Pos>+50% ranged damage resistance</Pos>
  - <Neg>-30% weapon damage</Neg>
  - Available on:
    - <Uni>Amputator</Uni>
<!-- - Unstable Mod: Vamprism Module
  - <Pos>On weapon hit: Heal nearby allies for 24 health, up to once every 0.17s</Pos>
  - <Pos>On weapon taunt: Apply the Battalion's Backup and Buff Banner effect to your team for 10s</Pos>
  - <Neu>When weapon is active:</Neu>
    - <Neg>-3 health regenerated per second</Neg>
    - <Neg>+20% damage vulnerability</Neg>
  - Available on:
    - <Uni>Amputator</Uni>-->

## Sniper
<h3 id="sniper_primary">Primary</h3>

- Unstable Mod: Rifle Mastery
  - <Pos>+20% weapon damage at full charge</Pos>
  - <Pos>+50% rifle charge rate</Pos>
  - <Pos>-40% zoom time</Pos>
  - <Neg>-65% weapon Explosive Headshot damage</Neg>
  - Available on:
    - <Nor>Sniper Rifle</Nor>
    - <Uni>Bazaar Bargain</Uni>
    - <Uni>Classic</Uni>
    - <Uni>Sydney Sleeper</Uni>
- Unstable Mod: Rifle Mastery
  - Same as above, but no <Pos>+20% weapon damage at full charge</Pos>.
  - Available on:
    - <Uni>Machina</Uni>
- Unstable Mod: Rubber Compound
  - <Pos>+300% weapon bleeding damage</Pos>
  - <Pos>Projectiles home to targets after 3.25s</Pos>
  - <Pos>Projectiles bounce off walls, retaining 95% of their speed after each bounce</Pos>
  - <Pos>Weapon projectiles cannot be reflected or deflected</Pos>
  - <Neg>No headshots</Neg>
  - <Neg>-25% damage vs players</Neg>
  - <Neg>Projectiles expire after 3.5s</Neg>
  - Available on:
    - <Uni>Huntsman</Uni>
- Unstable Mod: Seeker Rounds
  - <Pos>All players connected via Medigun beams are hit by weapon</Pos>
  - <Pos>Can headshot when not fully charged</Pos>
  - <Neg>-90% rifle charge rate</Neg>
  - <Neg>-50% weapon Explosive Headshot damage</Neg>
  - Available on:
    - <Uni>Classic</Uni>

<h3 id="sniper_secondary">Secondary</h3>

- Stable Mod: Debuff Rounds
  - <Pos>On weapon hit: One target at a time is Marked-For-Death for 15s</Pos>
  - Available on:
    - <Nor>SMG</Nor>
- Unstable Mod: Headshot Mode
  - <Pos>Weapon can headshot</Pos>
  - <Pos>Weapon has increased headshot explosion radius and damage to nearby enemies</Pos>
  - <Neg>-90% weapon Explosive Headshot damage</Neg>
  - <Neg>-50% weapon firing speed</Neg>
  - Available on:
    - <Nor>SMG</Nor>

<h3 id="sniper_melee">Melee</h3>

- Unstable Mod: Biohazard Blade ($200)
  - <Pos>On weapon hit: Apply 10s seconds of Jarate to target</Pos>
  - <Pos>+200% weapon bleed damage</Pos>
  - <Pos>+20% weapon bleed tick rate</Pos>
  - <Neg>-15% weapon damage</Neg>
  - Available on:
    - <Uni>Tribalman's Shiv</Uni>

## Spy
<h3 id="spy_primary">Primary</h3>

- Stable Mod: Combo Slugs
  - <Pos>+25% weapon damage</Pos>
  - <Pos>On weapon kill: Wearer gains Mini-crits for 5s.</Pos>
  - Available on:
    - <Nor>Revolver</Nor>
    - <Uni>Diamondback</Uni>
    - <Uni>L'Etranger</Uni>
- Unstable Mod: Magnum Chamber
  - <Pos>+50% weapon damage</Pos>
  - <Pos>+180% weapon damage while disguised</Pos>
  - <Pos>On Hit: One target at a time is Marked-For-Death for 15s</Pos>
  - <Neg>Hold fire to load 6 bullets</Neg>
  - <Neg>Auto-fires full clip once released</Neg>
  - <Neg>-50% weapon reload speed</Neg>
  - Available on:
    - <Uni>Enforcer</Uni>
- Unstable Mod: Tranq Rounds
  - <Pos>On weapon hit: One target at a time is Marked-For-Death for 15s</Pos>
  - <Pos>On weapon hit: Disable buildings for 4 seconds</Pos>
  - <Pos>On weapon hit: Victim loses up to 25% Medigun charge</Pos>
  - <Neg>Weapon rounds are replaced with syringes</Neg>
  - <Neg>-35% weapon damage vs players</Neg>
  - <Neg>-35% weapon clip size</Neg>
  - Available on:
    - <Nor>Revolver</Nor>
    - <Uni>Diamondback</Uni>
    - <Uni>L'Etranger</Uni>
- Unstable Mod: Explosive Headshot
  - <Pos>Weapon has increased headshot explosion radius and damage to nearby enemies</Pos>
  - <Pos>Critical damage is unaffected by range</Pos>
  - <Neg>-50% weapon reload speed</Neg>
  - <Neg>-20% weapon firing speed</Neg>
  - <Neg>-50% weapon clip size</Neg>
  - Available on:
    - <Uni>Ambassador</Uni>

<!--### Secondary -->
<!--### Melee-->

<h3 id="spy_pda2">PDA2</h3>

- Unstable Mod: Cash Vacuum
  - <Pos>+400% credit collection radius on wearer</Pos>
  - <Pos>Gain +40 health from collected credits</Pos>
  - Available on:
    - <Nor>Invis Watch</Nor>
    - <Uni>Cloak and Dagger</Uni>

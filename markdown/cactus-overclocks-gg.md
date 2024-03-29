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

<p></p>
General Notes

- If one somehow manages to have negative cash, upgrades are bugged and will not let you purchase them, even though they cost nothing.
- Clip size decreases do not always apply immediately, meaning upgrades that provide it can be exploited to begin the round with original clip capacity.

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
  - Notes:
    - <Neg>-150% weapon reload speed</Neg> is incorrectly listed as '100% slower reload'.
- Unstable Mod: Vintage Model
  - <Pos>Boost is not reduced on taking damage</Pos>
  - <Pos>+40% weapon accuracy</Pos>
  - <Neg>No double jump on wearer</Neg>
  - <Neg>-10% move speed on wearer</Neg>
  - Available on:
    - <Uni>Baby Face's Blaster</Uni>
  - Notes:
    - Base move speed change: 119.7%/360HU/s -> 106.4%/320HU/s
- Unstable Mod: Expanded Crit Module
  - <Pos>Weapon always crits from behind</Pos>
  - <Neg>-46% weapon accuracy</Neg>
  - <Neg>-25% weapon reload speed</Neg>
  - Available on:
    - <Uni>Back Scatter</Uni>
  - Notes:
    - <Pos>Weapon always crits from behind</Pos> does not appear to be as forgiving in angle as the <Uni>Back Scatter's</Uni> default stat <Pos>Mini-crits targets when fired at their back from close range</Pos>, but will of course work from any range.
- Unstable Mod: Special Delivery
  - <Pos>+25 max health on wearer</Pos>
  - <Pos>+46% weapon reload speed</Pos>
  - <Neg>No double jump on wearer</Neg>
  - <Neg>-30% weapon firing speed</Neg>
  - Available on:
    - <Uni>Shortstop</Uni>
  - Notes:
    - <Neg>Increase in push force taken from damage and airblast</Neg> appears to be altered to be provided globally rather than when active.
- Unstable Mod:: Slim Slugs
  - <Pos>+20% weapon accuracy</Pos>
  - <Pos>No weapon knockback on target</Pos>
  - <Neg>No weapon knockback on shooter</Pos>
  - <Neg>-15% weapon reload speed</Neg>
  - Available on:
    - <Uni>Force-a-Nature</Uni>
  - Notes:
    - The additional colon exists in-game.
    - When ghost upgraded with Firing Speed, the knockback removal stat used to occasionally bug; have since been unable to reproduce this behaviour since HH2 and this note will be removed if the bug is not reported any further.

<!--- Unstable Mod: Super Shells
  - <Pos>Hype effect is replaced with mini-crits</Pos>
  - <Neg>-25% weapon reload speed</Neg>
  - <Neg>-50% weapon accuracy</Neg>
  - Available on:
    - <Uni>Soda Popper</Uni>
  - Notes:
    - Effect override uses condition 19, meaning the <Uni>Crit-a-cola</Uni> will drain Hype effect when active.-->

<h3 id="scout_secondary">Secondary</h3>

- Stable Mod: Combo Bullets
  - <Pos>On weapon kill: Wearer gains Crits for 3s.</Pos>
  - <Pos>+25% weapon damage</Pos>
  - Available on:
    - <Nor>Pistol</Nor>
    - <Uni>Pretty Boy's Pocket Pistol</Uni>
    - <Uni>Winger</Uni>
  - Notes:
    - 'AllowPlayerClass Sniper' is provided for this upgrade, but does not target any sniper weapons.
- Unstable Mod: Dairy Mags
  - <Pos>On weapon hit: Apply 2.5s seconds of Mad Milk to target</Pos>
  - <Neg>-75% weapon firing speed</Neg>
  - Available on:
    - <Nor>Pistol</Nor>
    - <Uni>Pretty Boy's Pocket Pistol</Uni>
    - <Uni>Winger</Uni>
  - Notes:
    - The <Uni>Mad Milk</Uni> on hit is not additive and only refreshes the duration of the condition.
    - Buying -35% Speed on Target and swapping to this does not work.
- Stable Mod: Battalion's Bonk-up
  - <Neu>Replaces Bonk! Effect with Battalion's Backup effect</Neu>
  - <Pos>Stun and knockback immune during effect</Pos>
  - <Pos>Weapon taunt can be used while airborne</Pos>
  - Available on:
    - <Uni>Bonk! Atomic Punch</Uni>
  - Notes:
    - Effect override uses condition 26, meaning the <Uni>Battalion's Backup</Uni> will erase Hype effect if the Scout leaves its radius whilst both are active.
    - Appears to last 10s instead of the expected 8s, though this does not appear to be intended. Possibly a consequence of the condition used itself.
    - <Pos>Stun and knockback immune during effect</Pos> is unlisted, provided by condition 28.
      - The <Uni>Quick-Fix</Uni> particles may be misleading; the effect does not provide any healing.
    - <Pos>Weapon taunt can be used while airborne</Pos> is unlisted.
      - This means the taunt cannot be cancelled, but this weapon only applies its effect at the end of the taunt anyway.
- Stable Mod: Hot Knife
  - <Pos>On weapon hit: Target is ignited for 7.5s</Pos>
  - <Pos>On weapon hit: One target at a time is Marked-For-Death for 15s</Pos>
  - <Pos>All players connected via Medigun beams are hit by weapon</Pos>
  - <Neg>-50% weapon bleed damage</Neg>
  - Available on:
    - <Uni>Flying Guillotine</Uni>
  - Notes:
    - The unlisted <Pos>All players connected via Medigun beams are hit</Pos> attribute can prove to be a useful Uber Medic pick tool, as the <Uni>Flying Guillotine</Uni> always does a round 50 base damage, allowing crits to deal up to 150 damage.
    - Ignite is transferred down the medi-chain, causing targets further down the chain to take both their own ignite instance and the ignite damage of targets they are connected to.
      - Recall that the mediguns cause ignite to expire twice as fast.
      - The same rules apply to bleed application.
    - Mark-for-death is applied to whatever target is last in the medi-chain.
    - Given these mechanics, against Giant Medics it makes the most sense to use the <Uni>Flying Guillotine</Uni> on their target for maximum damage to the medic.
    - Against a single target, one cleaver will deal a total of 155 damage.

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
  - Notes:
    - Like the <Uni>Sandman's</Uni> default mark upgrade, both the <Uni>Wrap Assassin</Uni> and  <Uni>Sandman</Uni> can mark using their ball with this upgrade.
    - The <Uni>Wrap Assassin</Uni> deals negative melee damage (-9) with this upgrade, causing you to heal your target instead.
- Unstable Mod: Craftsman's Bat
  - <Pos>+15 max health on wearer</Pos>
  - <Pos>On weapon hit: Bleed target for 5s</Pos>
  - <Pos>+300% weapon bleeding damage</Pos>
  - <Neg>-35% swing speed</Pos>
  - Available on:
    - <Uni>Boston Basher</Uni>
    - <Uni>Sandman</Uni>
  - Notes:
    - Bleed damage multiplier also applies to yourself; if you miss with the Boston Basher and aren't buffed, you will die.
    - <Pos>+300% weapon bleeding damage</Pos> is incorrectly listed as '2x bleed damage'
    - `"mult bleeding dmg"` is accidentally defined twice for this upgrade, first at 3 and then at 2; the 4x bleed takes priority.
- Unstable Mod: Sugar Shock
  - <Pos>On weapon hit: One target at a time is Marked-For-Death for 15s</Pos>
  - <Pos>Wearer blast damage vulnerability removed</Pos>
  - <Pos>On weapon hit: Gain a speed boost for 5s</Pos>
  - <Neg>-15 max health on wearer</Neg>
  - Available on:
    - <Uni>Candy Cane</Uni>
- Unstable Mod: Soul Scorcher
  - <Pos>+600% base weapon damage vs burning players</Pos>
  - <Neg>90% damage penalty vs non-burning players</Neg>
  - Available on:
    - <Uni>Sun-on-a-Stick</Uni>
  - Notes:
    - <Pos>+600% base weapon damage vs burning players</Pos> is incorrectly listed as '6x damage to burning enemies'.
    - Deals 236 damage vs burning targets.
      - (35\*0.75\*3) + 6(35\*0.75) = 236.25
- Unstable Mod: Heavy Material
  - <Neu>When weapon is active:</Neu>
    - <Pos>-30% damage from ranged sources</Pos>
    - <Neg>-15% move speed</Neg>
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
  - Notes:
    - Rockets are assigned a -600HUs<sup>-2</sup> vertical acceleration, reducing their effective range from infinite to ~2017HU along flat ground fired at -45°.
    - <Neg>Clip Size cannot be upgraded</Neg> is unlisted.
      - This stat cannot be bypassed by purchasing Clip Size first; you will be unable to take this upgrade if you do.
    - <Pos>Weapon projectiles cannot be reflected or deflected</Pos> is unlisted.
- Unstable Mod: Extra Gunpowder
  - <Pos>+20% weapon damage</Pos>
  - <Pos>Weapon projectiles cannot be reflected or deflected</Pos>
  - <Neg>-20% weapon blast radius</Neg>
  - <Neg>-25% weapon clip size</Neg>
  - Available on:
    - <Uni>Direct Hit</Uni>
  - Notes:
    - Does not seem to outperform the <Uni>Beggar's Bazooka</Uni> at tank busting at any level of credit investment, under both crit and mini-crit conditions; implicitly, then, it would also fail to outperform the <Uni>Air Strike</Uni>.
    - Rocket jumping is still feasible even with the additional <Neg>-20% blast radius</Neg>.
    - <Pos>Weapon projectiles cannot be reflected or deflected</Pos> is unlisted.
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
  - Notes:
    - <Pos>On weapon hit: +40 health per enemy hit</Pos> works as the old <Uni>Black Box</Uni> attribute, replacing the limited health-on-hit attribute on the current stock variant.
    - Not that you'd need to, but you can't buy more Firing Speed than this weapon provides.
    - This upgrade defines `"heal on hit for rapidfire"` twice, also at +15, but the +40 takes priority.
    - It's possible to tapfire this to not shoot all rockets at once... just about. Not sure why you would want to with <Neg>Cannot fire until all rockets are loaded</Neg>.
      - If you are out of reserve ammo and 3 rockets aren't currently loaded, you will not be able to fire this weapon.
    - jump_sync has never been easier... if you can survive the jump cost. And shit aim.
- Unstable Mod: Tank Buster
  - <Pos>Heal-on-hit stacks vs multiple enemies</Pos>
  - <Pos>+20% weapon damage vs tanks</Pos>
  - <Neg>-25% weapon projectile speed</Neg>
  - Available on:
    - <Uni>Black Box</Uni>
  - Notes:
    - Heal-on-hit is reverted to pre-Gun Mettle behaviour, as on the previous upgrade.
- Unstable Mod: Jump Module
  - <Pos>+40% weapon firing speed</Pos>
  - <Pos>+35% weapon blast radius</Pos>
  - <Pos>+50% primary reserve ammo</Pos>
  - <Neg>-15% weapon damage</Neg>
  - Available on:
    - <Uni>Liberty Launcher</Uni>
- Unstable Mod: Smart Rockets
  - <Pos>0.06x weapon firing delay while blast jumping</Pos>
  - <Neu>Rockets home to crosshair position</Neu>
  - <Neg>-50% weapon clip size</Neg>
  - <Neg>-15% weapon damage</Neg>
  - <Neg>+25% self-damage from blast jumping</Neg>
  - <Neg>-35% weapon projectile speed</Neg>
  - <Neg>Rockets detonate after 2.5s</Neg>
  - Available on:
    - <Uni>Air Strike</Uni>
  - Notes:
    - Rocket turn rate is limited to 360°/s
    - Rocket range is now limited to 2750HU.
    - <Neg>-15% weapon damage</Neg> is unlisted.
    - <Pos>0.06x weapon firing speed while blast jumping</Pos> is incorrectly listed as '+25% increase to rocket jump bonuses'.
      - This is because `"rocketjump attackrate bonus"` is a positive multiplier of the default firing delay, so the real firing interval is about 0.048s.
    - Although the weapon lists '+25% increase to rocket jump *bonuses*', it does not actually apply <Neg>-25% weapon blast radius while blast jumping</Neg>, as this stat applies as a fixed 0.8 radius multiplier.

<h3 id="soldier_secondary">Secondary</h3>

- Stable Mod: Debuff Rounds
  - <Pos>On weapon hit: One target at a time is Marked-For-Death for 15s</Pos>
  - Available on:
    - <Nor>Shotgun</Nor>
    - <Uni>Panic Attack</Uni>
    - <Uni>Reserve Shooter</Uni>
  - Notes:
    - Shotguns hitting multiple targets appear to select mark target arbitrarily.
      - There's some kind of predictable bullet processing order, though I did not bother to determine this order as it would only be useful information with fixed weapon spread enabled.
- Unstable Mod: Air-raid rounds
  - <Pos>Weapon always crits while blast jumping</Pos>
  - <Pos>0.5x weapon firing delay while blast jumping</Pos>
  - <Pos>+50% weapon accuracy</Pos>
  - <Pos>Provides the B.A.S.E. Jumper to wearer</Pos>
  - <Neg>-50% weapon firing speed</Neg>
  - Available on:
    - <Uni>Reserve Shooter</Uni>
  - Notes:
    - <Pos>+100% weapon firing speed while blast jumping</Pos> is incorrectly listed as 'fires 40% faster while rocket jumping'.
      - Although written wrongly anyway, the significant difference from the stated value is caused by `"rocketjump attackrate bonus"` not being additive with the fire speed penalty on the weapon but rather is a positive multiplier of the base fire delay.
    - <Pos>Provides the B.A.S.E. Jumper to wearer</Pos> is unlisted.
    - <Uni>B.A.S.E. Jumper</Uni> upgrades do not apply if first bought then swapping to this upgrade.
- Stable Mod: Titanium Soles
  - <Pos>+200% credit collection radius on wearer</Pos>
  - <Pos>Wearer never takes falling damage</Pos>
  - <Pos>+25% primary reserve ammo</Pos>
  - <Neg>No weapon stomp damage</Neg>
  - Available on:
    - <Uni>Gunboats</Uni>
    - <Uni>Mantreads</Uni>
  - Notes:
    - <Neg>No stomp damage</Neg> is a side effect of taking no falling damage.
    - <Pos>+200% credit collection radius on wearer</Pos> is half of Scout's radial bonus.
- Unstable Mod: Slim Rockets
  - <Pos>+15% reload speed on wearer</Pos>
  - <Neg>-50% primary reserve ammo</Neg>
  - <Neg>-50% secondary reserve ammo</Neg>
  - Available on:
    - <Uni>B.A.S.E. Jumper</Uni>
    - <Uni>Gunboats</Uni>
  - Notes:
    - <Pos>+15% reload speed on wearer</Pos> is incorrectly listed as '+15% faster primary reload', but there's no functional difference on Soldier.
    - <Neg>-50% secondary reserve ammo</Neg> has no impact on Soldier.
- Unstable Mod: Heavy Duty Boots
  - <Pos>+175 stomp damage</Pos>
  - <Pos>+10% move speed on wearer<Pos>
  - Available on:
    - <Uni>Mantreads</Uni>
  - Notes:
    - `"kb fall min velocity" 150 "kb fall radius" 75 "kb fall force" 100 "kb fall stun time" -1` are declared for this upgrade, but do not appear to do anything.
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
  - <Pos>+35% weapon damage</Pos>
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
    - <Uni>Righteous Bison</Uni>
  - Notes:
    - Base damage of 66.
    - Projectile is in function replaced with a Huntsman arrow; its appearance is supposed to be replaced too like the <Uni>Crusader's Crossbow</Uni> to retain an energy theme but appears to currently be bugged.
    - <Neg>Clip Size cannot be upgraded</Neg> is unlisted.
    - Projectile is assigned a -300HUs<sup>-2</sup> vertical acceleration, but due to the short projectile lifetime and ability to bounce, effective range is generally limited by projectile expiration at 2400HU.
    - Projectile appears to retain the 1200HU/s velocity of the <Uni>Righteous Bison</Uni>, along with other properties such as no falloff. -->
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
  - Notes:
    - `"reload full clip at once" 1` does not work with clip size, but sigdemo does not appear to imply this to be the case. Likely a bug as the interaction does not occur with other weapon types like the <Uni>Crusader's Crossbow</Uni>.
    - Reload animations are fucked with clip size upgrades.
    - <Neg>-50% weapon reload speed</Neg> is incorrectly listed as '-100% reload speed'.
    - <Neg>Reload Speed cannot be upgraded</Neg> is unlisted.
    - Projectiles are now limited to 360HU.

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
  - Notes:
    - <Neg>On miss: Hit yourself, idiot</Neg> does not apply bleed; this is intrinsic to the <Uni>Boston Basher</Uni>. Self-damage is half of weapon damage.
- Unstable Mod: Magnetic Spike
  - <Pos>+150% melee range</Pos>
  - <Pos>+100% credit collection radius on wearer</Pos>
  - <Pos>+35% weapon damage</Pos>
  - <Neg>+10% bullet damage taken</Neg>
  - Available on:
    - <Uni>Pain Train</Uni>
  - Notes:
    - <Pos>+35% weapon damage</Pos> is unlisted.
    - <Pos>+150% melee range</Pos> is incorrectly listed as '+100% melee range'.
    - <Pos>+100% credit collection radius on wearer</Pos> is a quarter of Scout's radial bonus.
- Unstable Mod: Titanic Toppler
  - <Pos>All players connected via Medigun beams are hit by weapon</Pos>
  - <Pos>+100% weapon damage vs Giants</Pos>
  - <Pos>+50% melee range</Pos>
  - <Neg>-15% weapon attack speed</Neg>
  - Available on:
    - <Uni>Market Gardener</Uni>
  - Notes:
    - <Pos>+50% melee range</Pos> is unlisted.
- Stable Mod: Combo Swing
  - <Pos>On weapon kill: Wearer gains Crits for 4s.</Pos>
  - <Pos>+100% melee range</Pos>
  - Available on:
    - <Uni>Market Gardener</Uni>
  - Notes:
    - <Pos>+100% melee range</Pos> is unlisted.
- Stable Mod: Survival Training
  - <Pos>+25% weapon damage</Pos>
  - <Pos>-35% damage taken from ranged sources while active</Pos>
  - Available on:
    - <Uni>Equalizer</Uni>
  - Notes:
    - The description lists <Neg>'-On miss: Hit yourself, idiot.'</Neg> but this attribute is not applied.
- Unstable Mod: Samurai Spirit
  - <Pos>+20% weapon attack speed
  - <Pos>On weapon kill: Wearer gains Mini-crits for 2s.</Pos>
  - <Neu>When weapon is active:</Neu>
    - <Pos>+10% move speed</Pos>
    - <Neg>+15% damage vulnerability</Neg>
  - Available on:
    - <Uni>Half-Zatoichi</Uni>
  - Notes:
    - Base move speed change: 80%/240HU/s -> 96%/288HU/s

## Pyro
<h3 id="pyro_primary">Primary</h3>

- Unstable Mod: Caustic Fumes
  - <Pos>On weapon hit: Apply Gas to target</Pos>
  - <Neg>Airblast no longer pushes back players</Neg>
  - Available on:
    - <Nor>Flamethrower</Nor>
  - Notes:
    - The weapon lists <Pos>Slow enemies on hit</Pos>, but it does not appear to do anything on the <Nor>Flamethrower</Nor>.
    - <Pos>On Hit: Apply Gas to target</Pos> is incorrectly listed as 'Ignite non-ignitable targets'; in particular, this wording ignores the fact that the <Nor>Flamethrower</Nor> will now always apply a full 10s afterburn.
      - The duration of the gas condition is infinite, but this doesn't particularly matter; the applying hit will trigger it.
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
  - <Neg>-15% weapon damage</Neg>
  - Available on:
    - <Uni>Degreaser</Uni>
  - Notes:
    - Base move speed change: 100%/300HU/s -> 110%/330HU/s

<h3 id="pyro_secondary">Secondary</h3>

- Stable Mod: Titanium Soles
  - <Pos>+200% credit collection radius on wearer</Pos>
  - <Pos>Wearer never takes falling damage</Pos>
  - <Pos>+25% primary reserve ammo</Pos>
  - Available on:
    - <Uni>Thermal Thruster</Uni>
  - Notes:
    - <Pos>+200% credit collection radius on wearer</Pos> is half of Scout's radial bonus.
- Unstable Mod: Heavy Duty Boots
  - <Pos>+175 stomp damage</Pos>
  - <Pos>+10% move speed on wearer<Pos>
  - Available on:
    - <Uni>Thermal Thruster</Uni>
  - Notes:
    - `"kb fall min velocity" 150 "kb fall radius" 75 "kb fall force" 100 "kb fall stun time" -1` are declared for this upgrade, but do not appear to do anything.
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
  - <Pos>+35% weapon damage</Pos>
  - <Neg>-35% weapon projectile speed</Neg>
  - <Neg>-80% weapon afterburn duration</Neg>
  - <Neg>-50% primary reserve ammo</Neg>
  - Available on:
    - <Uni>Flare Gun</Uni>
  - Notes:
    - <Pos>+35% weapon damage</Pos> is incorrectly listed as '+50% damage bonus.
- Unstable Mod: Volcanic Compound
  - <Pos>+35% weapon blast radius</Pos>
  - <Pos>+50% weapon afterburn tick rate</Pos>
  - <Neg>-50% weapon damage</Neg>
  - <Neg>-35% weapon projectile speed</Neg>
  - Available on:
    - <Uni>Detonator</Uni>
    - <Uni>Scorch Shot</Uni>
  - Notes:
    - <Neg>-35% weapon projectile speed</Neg> is interpretable as a positive with the <Uni>Detonator</Uni> as it increases the length of the effective manual detonation window.
- Unstable Mod: Molten Core
  - <Pos>+200% weapon afterburn tick rate</Pos>
  - <Pos>On weapon hit: Bleed target for 3s</Pos>
  - <Pos>+300% weapon bleed damage</Pos>
  - <Neg>-50% weapon projectile speed</Neg>
  - Available on:
    - <Uni>Manmelter</Uni>
  - Notes:
    - <Pos>+300% weapon bleed damage</Pos> is unlisted.
    - For whatever reason, <Pos>On weapon hit: Bleed target for 3s</Pos> is only accurate against Giants; regular robots bleed for about 12s. This effect occurs even with no other attributes present on the upgrade. This effect is not reproducible with other weapons that I tested, like the <Uni>Boston Basher</Uni> or <Uni>Pomson 6000</Uni>. TODO: wtf?
- Unstable Mod: Trench Gun
  - <Pos>Fires +20% bullets per shot</Pos>
  - <Pos>On weapon hit: target is ignited for 7.5s</Pos>
  - <Pos>+150% weapon afterburn tick rate</Pos>
  - <Neg>-35% weapon accuracy</Neg>
  - Available on:
    - <Nor>Shotgun</Nor>
    - <Uni>Reserve Shooter</Uni>
  - Notes:
    - <Pos>On weapon hit: target is ignited for 7.5s</Pos> is defined as `"Set DamageType Ignite" 5`, but it only accepts a boolean value.
    - <Pos>+150% weapon afterburn tick rate</Pos> is unlisted.
- Unstable Mod: Australian Gas
  - <Pos>Weapon now coats players in Jarate</Pos>
  - <Neg>-75% weapon effect duration</Neg>
  - Available on:
    - <Uni>Gas Passer</Uni>
  - Notes:
    - Base effect duration 10s -> 2.5s.
    - You can draw the weapon while it is not charged with this upgrade, but you will not be able to use it until it is charged.
    - The lingering effect of the gas cloud is bugged and does not apply <Uni>Jarate</Uni>, but instead Gas. Enemies will not be inflicted with Gas if they are stood in the initial application radius.
    - <Neg>-75% weapon effect duration</Neg> is incorrectly listed as '-70% effect duration'.

<h3 id="pyro_melee">Melee</h3>

- Unstable Mod: Heavy Mallet
  - <Neg>-25% weapon damage vs players</Neg>
  - <Neu>When weapon is active:</Neu>
    - <Pos>-35% bullet damage taken</Pos>
    - <Pos>-90% push force taken from damage</Pos>
  - Available on:
    - <Uni>Homewrecker</Uni>
  - Notes:
    - <Pos>-90% push force taken from damage</Pos> affects purely damage push force; rocket knockback, airblast etc. will launch you as usual.
- Unstable Mod: Gordbort Capacitor
  - <Pos>All players connected via Medigun beams are hit by weapon</Pos>
  - <Neg>-25% weapon attack speed</Neg>
  - Available on:
    - <Uni>Neon Annihilator</Uni>
  - Notes:
    - Condition inheritance follows previously discussed rules for the <Uni>Sun-on-a-stick</Uni> upgrade
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
- Unstable Mod: Spine Zapper
  - <Pos>Weapon always crits from behind</Pos>
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
  - Notes:
    - <Pos>+55% weapon swing radius</Pos> is unlisted.
    - Both range modifiers mimic the hidden stats of the <Uni>Disciplinary Action</Uni>.

## Demoman
<h3 id="demoman_primary">Primary</h3>

- Unstable Mod: Slim Rockets
  - <Pos>+15% reload speed on wearer</Pos>
  - <Neg>-50% primary reserve ammo</Neg>
  - <Neg>-50% secondary reserve ammo</Neg>
  - Available on:
    - <Uni>B.A.S.E. Jumper</Uni>
  - Notes:
    - <Pos>+15% reload speed on wearer</Pos> is incorrectly listed as '+15% faster primary reload'.
    - <Neg>-50% primary reserve ammo</Neg> has no impact on Demoman.
- Stable Mod: Improved Parachute
  - <Pos>200% increased air control on wearer</Pos>
  - <Pos>Parachute re-deploy allowed</Pos>
  - Available on:
    - <Uni>B.A.S.E. Jumper</Uni>
  - Notes:
    - This upgrade also provides <Pos>+50% primary reserve ammo</Pos>, but this weapon occupies Demoman's primary slot.
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
  - Notes:
    - <Neg>+3 degrees random weapon projectile deviation</Neg> is incorrectly listed as '2 degrees of deviation'.
- Unstable Mod: Burst Chamber
  - <Pos>Weapon fires a bonus pipebomb per round</Pos>
  - <Pos>Launched bombs do not shatter on surfaces</Pos>
  - <Neg>-35% weapon damage</Neg>
  - <Neg>-50% weapon blast radius</Neg>
  - <Neg>-50% weapon damage on contact with surfaces</Neg>
  - Available on:
    - <Uni>Loch-n-Load</Uni>
  - Notes:
    - <Pos>Launched bombs do not shatter on surfaces</Pos> is unlisted.
    - <Neg>-50% weapon damage on contact with surfaces</Neg> is unlisted.
    - `"mult projectile count"` seems to intrinsically cause projectile origin position to be random, causing this weapon to be fairly inaccurate.
- Unstable Mod: Blunderbuss
  - <Pos>On weapon hit: Refill 75% of your shield charge meter</Pos>
  - <Pos>On weapon kill: Gain all banner effects for 4s</Pos>
  - <Pos>Cannonballs explode on impact</Pos>
  - <Pos>+20% weapon damage</Pos>
  - <Pos>-75% self damage taken from blast jumping</Pos>
  - <Neg>-50% weapon clip size</Neg>
  - Available on:
    - <Uni>Loose Cannon</Uni>
  - Notes:
    - <Pos>On weapon kill: Gain all banner effects for 4s</Pos> is unlisted.
      - Mini-crits last for 5s instead of 4s.
    - <Pos>-75% self damage taken from blast jumping</Pos> is unlisted.
    - <Pos>Cannonballs explode on impact</Pos> makes landing Double-donks trivial.
    - Banners are applied as `"add cond on kill" 7450` and `"minicritboost on kill" 5`
      - This upgrade provides both conditions 26 and 29, which means they this upgrade will conflict with the respective banners, but the mini-crits component will not.
    - `"grenade launcher mortar mode" 0` is defined but does not appear to do anything.
- Unstable Mod: Cash Magnet
  - <Pos>+200% credit collection radius on wearer</Pos>
  - <Neg>-75% reload speed on wearer</Neg>
  - <Neg>-25 max health on wearer</Neg>
  - <Neg>-50% secondary reserve ammo</Neg>
  - Available on:
    - <Uni>Ali Baba's Wee Booties</Uni>
  - Notes:
    - <Pos>+200% credit collection radius on wearer</Pos> is half of Scout's radial bonus.
    - <Pos>Stickybombs stick to enemies</Pos> is defined for this weapon, but does nothing nature of not being a stickybomb launcher.

<h3 id="demoman_secondary">Secondary</h3>

- Stable Mod: Titanium Soles
  - <Pos>+200% credit collection radius on wearer</Pos>
  - <Pos>Wearer never takes falling damage</Pos>
  - <Pos>+25% primary reserve ammo</Pos>
  - Available on:
    - <Uni>Sticky Jumper</Uni>
  - Notes:
    - <Pos>+200% credit collection radius on wearer</Pos> is half of Scout's radial bonus.
- Unstable Mod: Extra Adhesive
  - <Pos>-0.1s weapon sticky arm time</Pos>
  - <Pos>Stickybombs stick to enemies</Pos>
  - <Neg>-3 max stickybombs out</Neg>
  - Available on:
    - <Nor>Stickybomb Launcher</Nor>
  - Notes:
    - <Pos>-0.1s sticky bomb arm time</Pos> is incorrectly listed as '10% faster arm-time'.
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
  - Notes:
    - <Pos>Stickybombs stick to enemies</Pos> is unlisted.
    - <Pos>-0.4s weapon sticky arm time</Pos> is unlisted.
    - <Neg>-1000% max sticky charge time</Neg> causes you to be unable to charge stickies past minimum range.
- Unstable Mod: Prototype Sensor
  - <Pos>+25% weapon clip size</Pos>
  - <Pos>+15% weapon damage at full charge</Pos>
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
  - Notes:
    - <Neg>-70% reload speed on wearer</Neg> is incorrectly listed as '-35% primary reload'.
- Unstable Mod: Pocket Incinerator
  - <Pos>+40 health from collected credits</Pos>
  - <Neg>-75% reload speed on wearer</Neg>
  - <Neg>-25% fire damage resistance on wearer</Neg>
  - <Neg>-15% blast damage resistance on wearer</Neg>
  - Available on:
    - <Uni>Chargin' Targe</Uni>
  - Notes:
    - <Pos>+40 health from collected credits</Pos> is capable of providing uncapped overheal.
    - <Pos>Stickybombs stick to enemies</Pos> is defined, but does nothing by nature of equipment choice.
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
  - Notes: 
    - <Neg>-15% fire damage resistance on wearer</Neg> is incorrectly listed at -25%.

<h3 id="demoman_melee">Melee</h3>

- Unstable Mod: Magnetic Spike
  - <Pos>+150% melee range</Pos>
  - <Pos>+100% credit collection radius on wearer</Pos>
  - <Pos>+35% weapon damage</Pos>
  - <Neg>+10% bullet damage taken</Neg>
  - Available on:
    - <Uni>Pain Train</Uni>
  - Notes:
    - <Pos>+35% weapon damage</Pos> is unlisted.
    - <Pos>+150% melee range</Pos> is incorrectly listed as '+100% melee range'.
    - <Pos>+100% credit collection radius on wearer</Pos> is a quarter of Scout's radial bonus.
- Unstable Mod: Gardener Module
  - <Pos>Weapon deals crits while blast jumping</Pos>
  - <Pos>+25% melee range</Pos>
  - <Neg>-10% weapon attack speed</Neg>
  - Available on:
    - <Nor>Bottle</Nor>
  - Notes:
    - <Pos>+25% melee range</Pos> is unlisted.
- Unstable Mod: Cushioned Explosive
  - <Pos>No weapon self-knockback</Pos>
  - <Neg>+50% weapon self damage</Neg>
  - <Neg>-25 max health on wearer</Neg>
  - Available on:
    - <Uni>Ullapool Caber</Uni>
  - Notes:
    - While <Pos>Explosive charge is not expended on use</Pos> is present on this weapon, it does not appear to function.
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
    - <Nor>Minigun</Nor>
  - Notes:
    - <Pos>Knockback Rage applies Rocket Specialist</Pos> is unlisted.
    - Rage lasts 10s by default instead of 5s without snapshotting.
    - <Neg>Projectiles expire after 3s</Neg> is defined, but is overriden by <Neg>Projectiles detonate after 2.8s</Neg>.
    - Rocket turn rate is limited to 360°/s.
    - Naming is inconsistent with other upgrades.
    - Additional ticks of Knockback Rage do not apply more Rocket Specialist ticks.
    - Note that <Neg>Cannot be revved</Neg> means this upgrade will frequently encounter the minigun implicit damage penalty period.
    - This upgrade still inherits the implicit minigun tank damage penalty.
    - Destroy Projectiles predictably does not appear to work well with this upgrade. 
    - Rockets have the default projectile speed of 1100HU/s. -->
- Unstable Mod: Defense Framework
  - <Pos>Can be holstered while spinning</Pos>
  - <Pos>+30% damage resistance when below 50% health and spun up</Pos>
  - <Pos>50% critical damage resistance on wearer</Pos>
  - <Pos>No spin up time penalty</Pos>
  - <Neg>-100% maximum overheal while active</Neg>
  - <Neg>Cannot move while weapon is deployed</Neg>
  - Available on:
    - <Uni>Brass Beast</Uni>
  - Notes:
    - <Neg>-100% maximum overheal while active</Neg> suffers from the same bug as the <Uni>Fists of Steel</Uni> and thus can be ignored by recieving overheal first when weapon is inactive.
    - <Pos>Can be holstered while spinning</Pos> is unlisted.
    - <Pos>+30% damage resistance when below 50% health and spun up</Pos> is listed incorrectly as '+30% Spinup resistance.
    - <Pos>50% critical damage resistance</Pos> seems to be granted as crit damage ignores spinup resistance in TF2.
- Unstable Mod: Leadstorm
  - <Pos>+20% weapon damage</Pos>
  - <Pos>-30% to spin up time</Pos>
  - <Pos>Can be holstered while spinning</Pos>
  - <Neg>-25% primary ammo capacity</Neg>
  - <Neg>Cannot move while weapon is deployed</Neg>
  - <Neg>No spun up damage resistance</Neg>
  - Available on:
    - <Uni>Natascha</Uni>
  - Notes:
    - <Pos>Can be holstered while spinning</Pos> is unlisted.
    - `"spunup_push_force_immunity" 1.0` is defined for this weapon, but does nothing.
- Unstable Mod: Optimized Barrel
  - <Pos>No movement penalty when spun up</Pos>
  - <Pos>Knockback Rage now instead causes attacks to pierce damage resistance effects and bonuses</Pos>
  - <Pos>Can be holstered while spinning</Pos>
  - <Neg>-50% primary ammo capacity</Neg>
  - Available on:
    - <Uni>Tomislav</Uni>
  - Notes:
    - <Pos>Can be holstered while spinning</Pos> is unlisted.
    - Rage lasts 10s by default instead of 5s without snapshotting.
    - Additional ticks of Knockback Rage apply no further bonus.
- Unstable Mod: Bigger Bullets
  - <Pos>+10% weapon damage</Pos>
  - <Pos>Knockback Rage now instead applies afterburn</Pos>
  - <Neg>Consumes an additional 3 ammo per second while spun up</Neg>
  - Available on:
    - <Uni>Huo-Long Heater</Uni>
  - Notes:
    - Rage lasts 10s by default instead of 5s without snapshotting.
    - `Set DamageType Ignite 5` is used to cause afterburn, but the key only accepts a boolean value.

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
  - Notes:
    - Uses 2 ticks of Destroy Projectiles; only requires one hit to destroy. Deflection event interval doesn't matter as the <Uni>Family Business</Uni> can't fire that fast.
      - Legitimately using this upgrade for the deflection bonus is a poor choice in any case.
- Stable Mod: Mannly Meal
  - <Pos>+175% to gesture speed on wearer</Pos>
  - <Pos>Consuming also grants Concheror effect</Pos>
  - Available on:
    - <Uni>Buffalo Steak Sandvich</Uni>
  - Notes:
    - This upgrade provides conditions 41, 29 and 16. This of course means that the <Uni>Concheror</Uni> will interfere with the buff provided, but also means that the  <Uni>Buff Banner</Uni> will too, as condition 16 is presumably used incorrectly instead of 19.

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
  - Notes:
    - I believe the 'short period' is 0.5s after a complete switch could first occur in the case of weapons that apply this stat?
    - 'Gru' in upgrade name is not capitalized in-game.

<!-- - Unstable Mod: Fuzzier Wool
  - <Pos>Crits whenever it would normally mini-crit</Pos>
  - <Neg>-15% weapon attack speed</Neg>
  - Available on:
    - <Uni>Holiday Punch</Uni> -->
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
  - <Neg>-50% weapon attack speed</Neg>
  - <Neg>Honorbound: Once drawn sheathing deals 50 damage to yourself unless it kills.</Neg>
  - Available on:
    - <Uni>Warrior's Spirit</Uni>
- Unstable Mod: Heavy Duty Steel
  - <Pos>+40% ranged damage resistance</Pos>
  - <Neg>-20% move speed on wearer</Neg>
  - <Neg>+100% increased melee damage vulnerability</Neg>
  - <Neg>-60% maximum overheal</Neg>
  - Available on:
    - <Uni>Fists of Steel</Uni>
  - Notes:
    - The now total <Neg>-100% maximum overheal</Neg> on this weapon is still subject to the weapon swap bug. Also note that the wording allows Overheal Expert to still apply overheal, and that the reversing the bug to apply a cap on overheal can be exploited for a faster uber build rate.

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

<!-- - Unstable Mod: Sentry Companion A.I
  - <Pos>+30% sentry range</Pos>
  - <Pos>+30% weapon damage to your sentry's target</Pos>
  - <Neg>Per Shot: -25 metal</Neg>
  - Available on:
    - <Uni>Widowmaker</Uni>
  - Notes:
    - <Pos>+30% sentry range</Pos> is incorrectly listed as '+25% sentry range'. -->
- Unstable Mod: Custom Engineered Shotgun
  - <Pos>Alt-Fire: Use 150 metal to pick up your targeted building from long range</Pos>
  - <Neg>Self mark-for-death when hauling buildings</Neg>
  - Available on:
    - <Nor>Shotgun</Nor>
    - <Uni>Frontier Justice</Uni>
- Unstable Mod: Improved Transistors
  - <Pos>Alt-Fire: Use 100 metal to pick up your targeted building from long range</Pos>
  - <Pos>+100% weapon damage</Pos>
  - <Pos>+100% weapon projectile speed</Pos>
  - <Pos>On weapon hit: Bleed for 1s</Pos>
  - <Pos>Projectile penetrates teammates</Pos>
  - <Pos>Projectile penetrates enemy targets</Pos>
  - Available on:
    - <Uni>Pomson 6000</Uni>
  - Notes:
    - <Pos>Projectile penetrates enemy targets</Pos> also causes the laser to appear as the <Uni>Righteous Bison</Uni> projectile, as listed in-game.
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
  - Notes:
    - `"reload full clip at once" 1` does not work with clip size, but sigdemo does not appear to imply this to be the case. Likely a bug as the interaction does not occur with other weapon types like the <Uni>Crusader's Crossbow</Uni>.
    - Reload animations are fucked with clip size upgrades.
    - <Neg>-50% weapon reload speed</Neg> is incorrectly listed as '-100% reload speed'.
    - <Neg>Reload Speed cannot be upgraded</Neg> is unlisted.
    - Projectiles are now limited to 360HU.
- Unstable Mod: Compact Sensor
  - <Pos>Long-range haul cost reduced to 50 metal</Pos>
  - <Neg>-25% max metal on wearer</Neg>
  - <Neg>-16% weapon clip size</Neg>
  - Available on:
    - <Uni>Rescue Ranger</Uni>
  - Notes:
    - <Neg>16% reduced clip size</Neg> is incorrectly listed as '-15% clip size', but has no functional difference.

<h3 id="engineer_secondary">Secondary</h3>

- Stable Mod: Sentry Companion
  - <Pos>+50% max building health</Pos>
  - <Pos>Teleporters can be used in both directions</Pos>
  - Available on:
    - <Nor>Pistol</Nor>
  - Notes:
    - Total max building health with this weapon and 3 ticks of Building Health is 1296HP... just shy of the<Uni> Wrangler's</Uni> 2592eHP maximum.
- Stable Mod: Combat Sensor
  - <Pos>+50% damage bonus to your sentry's target</Pos>
  - <Pos>On Kill: Gain Mini-crits for 6 seconds.</Pos>
  - <Pos>-25% building cost</Pos>
  - Available on:
    - <Nor>Pistol</Nor>
  - Notes:
    - Mini-crit boost applies to sentries.
- Unstable Mod: Sentry Jumper
  - <Pos>-95% self-damage taken from blast jumping</Pos>
  - <Pos>Wearer never takes falling damage</Pos>
  - <Neg>-15% max metal on wearer</Neg>
  - Available on:
    - <Uni>Wrangler</Uni>
  - Notes:
    - <Pos>Wearer never takes falling damage</Pos> is unlisted.
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
  - Notes:
    - Explosive bullets have a blast radius of 100HU.
    - <Pos>Weapon range increased to 750HU</Pos> is unlisted.
    - <Pos>+500% weapon damage</Pos> is unlisted.
    - <Neg>-35% weapon damage vs players</Neg> is unlisted.
    - <Neg>+25% to self blast damage on wearer</Neg> in unlisted. Note that it applies to sentry rockets.
    - Self blast propulsion appears to be stronger than the <Uni>Detonator</Uni>, whilst dealing less self damage.
      - This means that c-tapping will increase blast jump height.
      - The blast from this weapon is not strong enough to pogo, but it is strong enough to wallclimb.
      - This weapon is hitscan, time your jumps accordingly. This also means that the explosives are effectively centerfired.
    - <Pos>Weapon bullets destroy projectiles in-flight</Pos> is unlisted.
      - Uses 2 ticks of Destroy Projectiles; only requires one hit to destroy. Deflection event interval doesn't matter as the <Uni>Short Circuit</Uni> can't fire that fast with this upgrade.

<h3 id="engineer_melee">Melee</h3>

- Stable Mod: Mobile Processors
  - <Pos>Grants an additional Disposable Sentry</Pos>
  - <Pos>+200% to dispenser health, ammo and metal output rate</Pos>
  - <Pos>+50% sentry range</Pos>
  - <Pos>Teleporter recharges 50% faster</Pos>
  - <Pos>+25% weapon damage</Pos>
  - Available on:
    - <Uni>Gunslinger</Uni>
  - Notes:
    - <Pos>+50% sentry range</Pos> is unlisted.
    - <Pos>+200% to dispenser health, ammo and metal output rate</Pos> is incorrectly listed as '+50% more effecient dispenser'.
      - Note that metal is not generated faster, but instead generates and dispenses in 3x quantity. Maximum metal capacity on the dispenser is not increased.
      - Ammo dispenses in 3x quantity, it does not dispense 3x faster.
      - Health is dispensed 3x faster.
    - `"construction rate increased" 2` is declared twice on this upgrade.
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
  - Notes:
    - Note that the <Uni>Wrangler</Uni> provides higher DPS at any level of Sentry Firing Speed; this upgrade only provides higher single target than the <Uni>Wrangler</Uni> over the duration of a crit canteen.
      - This makes the <Uni>Jag</Uni> perhaps still superior in some rare scenarios for its increased metal refill rate, which synergises better with the <Uni>Wrangler</Uni>.


## Medic
<h3 id="medic_primary">Primary</h3>

- Unstable Mod: Support Bolts
  - <Pos>On weapon hit: Apply 4s seconds of Mad Milk to target</Pos>
  - <Neg>-75% weapon reload speed</Neg>
  - <Neg>-50% weapon damage</Neg>
  - Available on:
    - <Uni>Crusader's Crossbow</Uni>
  - Notes:
    - This has the same base duration as the Mad Milk Syringe's maximum.
- Unstable Mod: Burst Reload
  - <Pos>Weapon reloads its entire clip at once</Pos>
  - <Neg>-50% weapon reload speed</Neg>
  - <Neg>-20% weapon damage</Neg>
  - <Neg>Reload Speed cannot be upgraded</Neg>
  - Available on:
    - <Uni>Crusader's Crossbow</Uni>
  - Notes:
    - <Neg>Reload Speed cannot be upgraded</Neg> is unlisted.
- Unstable Mod: Biohazard Needle
  - <Pos>On weapon hit: Apply 2s seconds of Jarate to target</Pos>
  - <Neg>-35% weapon reload speed</Neg>
  - <Neg>-75% weapon clip size</Neg>
  - <Neg>-75% weapon damage</Neg>
  - Available on:
    - <Nor>Syringe Gun</Nor>
    - <Uni>Blutsauger</Uni>
    - <Uni>Overdose</Uni>
  - Notes:
    - The clip size and reload penalty on this upgrade is still sufficient to keep up both <Uni>Jarate</Uni> and <Uni>Mad Milk</Uni> on a single target indefinitely without upgrade.

<h3 id="medic_secondary">Secondary</h3>

- Unstable Mod: Broken Shield Lens
  - <Pos>+20% weapon heal rate</Pos>
  - <Pos>+5% ÜberCharge rate on Overhealed patients</Pos>
  - <Neg>-100% Projectile Shield damage</Neg>
  - <Neg>-65% Projectile Shield duration</Neg>
  - Available on:
    - <Nor>Medi Gun</Nor>
    - <Uni>Kritzkrieg</Uni>
  - Notes:
    - This upgrade causes Projectile Shield to heal enemies by 196 over its whole duration.
- Unstable Mod: Prototype Module
  - <Pos>+50% weapon heal rate</Pos>
  - <Pos>Heal buildings at a rate of 40%/s</Pos>
  - <Neg>-50% maximum overheal</Neg>
  - <Neg>-20% ÜberCharge rate on Overhealed patients</Neg>
  - <Neg>-20% overheal duration</Neg>
  - Available on:
    - <Uni>Quick-Fix</Uni>
  - Notes:
    - Overheal Expert allows this medigun to still overheal despite its further 50% overheal penalty.
    - <Neg>-20% overheal duration</Neg> is unlisted.
      - Self-overheal during uber seems to be affected by both this and the overheal penalty, along with Overheal Expert.
    - Uber build rate is roughly equivalent to a non-overhealed player at maximum health against buildings
      - Heal rate against buildings appears to be constant, and also idk how you would ever kill a sentry tanked by a medic with this.

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
    - <Uni>Amputator</Uni>
  - Notes:
    - This upgrade provides both conditions 26 and 16, which means they will conflict with their respective banners if both this upgrade and banners are active simultaneously.
    - Note that the medic does not recieve the buffs from taunting, but instead on weapon hit, overriding the heal component. Teammates do not receive buffs on hit, only the heal component. This seems to be caused by an oversight in the interaction between `"effect cond override"` and `"aoe heal chance"`. -->

## Sniper
<h3 id="sniper_primary">Primary</h3>

- Unstable Mod: Rifle Mastery
  - <Pos>+50% rifle charge rate</Pos>
  - <Pos>-40% zoom time</Pos>
  - <Neg>-50% weapon Explosive Headshot damage</Neg>
  - Available on:
    - <Nor>Sniper Rifle</Nor>
    - <Uni>Bazaar Bargain</Uni>
    - <Uni>Classic</Uni>
    - <Uni>Sydney Sleeper</Uni>
  - Notes:
    - <Pos>-40% zoom time</Pos> is bugged in the same manner as reload speed; it applies only to consecutive re-zooms, so `cl_autorezoom 1` must be set to notice a beneift, or one must hold down right click between shots with `cl_autorezoom 0`.
      - Note that increases to zoom time also cause shots to start charging faster.
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
  - Notes:
    - Arrow turn rate is limited to 360°/s.
    - <Pos>Projectiles home to targets after 3.25s</Pos> is incorrectly listed as 'Arrows will seek target after 3 seconds'.
    - <Neg>Projectiles expire after 3.5s</Neg> is unlisted.
- Unstable Mod: Seeker Rounds
  - <Pos>All players connected via Medigun beams are hit by weapon</Pos>
  - <Pos>Can headshot when not fully charged</Pos>
  - <Neg>-90% rifle charge rate</Neg>
  - <Neg>-50% weapon Explosive Headshot damage</Neg>
  - Available on:
    - <Uni>Classic</Uni>
  - Notes:
    - As a specific use case, this could avoid Uber Medics popping when they overheal each other as it applies the base damage of the shot to each, rather than the maximum of 190 on the Explosive Headshot upgrade.

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
  - Notes:
    - <Pos>Increased headshot explosion radius and damage to nearby enemies</Pos> is equivalent to one tick of Explosive Headshot.
    - This seems like it would be more useful for its stun ability rather than damage, but note it has only slightly worse DPS vs a single target to a <Uni>Hitman's Heatmaker</Uni> that is focused with 3 ticks of reload speed; it has superior DPS to an unfocus rifle with the same reload speed upgrades.

<h3 id="sniper_melee">Melee</h3>

- Unstable Mod: Biohazard Blade
  - <Pos>On weapon hit: Apply 10s seconds of Jarate to target</Pos>
  - <Pos>+200% weapon bleed damage</Pos>
  - <Pos>+20% weapon bleed tick rate</Pos>
  - <Neg>-15% weapon damage</Neg>
  - Available on:
    - <Uni>Tribalman's Shiv</Uni>
  - Notes:
    - Deals ~263 damage total in a single swing over bleed duration.
    - <Pos>On weapon hit: Apply 10s seconds of Jarate to target</Pos> is incorrectly listed as 'Applies Jarate for 3 seconds'.
      - It is defined to only last for 5s, but applies for 10s anyway.

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
  - Notes:
    - Holding fire to reload does not break diguise.
    - This weapon still reloads its entire chamber at once.
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
  - Notes:
    - Generally this weapon is not much faster at killing multiple sentries than using the <Nor>Revolver</Nor> and shooting at the currently sapped one, one at a time.
    - The <Uni>Red-tape Recorder</Uni> is generally faster at killing sentries with bolstered health than both of these methods.
- Unstable Mod: Explosive Headshot
  - <Pos>Weapon has increased headshot explosion radius and damage to nearby enemies</Pos>
  - <Pos>Critical damage is unaffected by range</Pos>
  - <Neg>-50% weapon reload speed</Neg>
  - <Neg>-20% weapon firing speed</Neg>
  - <Neg>-50% weapon clip size</Neg>
  - Available on:
    - <Uni>Ambassador</Uni>
  - Notes:
    - <Pos>Increased headshot explosion radius and damage to nearby enemies</Pos> is equivalent to one tick of Explosive Headshot.
    - <Neg>-20% weapon firing speed</Neg> is not necessarily a significant downside on the <Uni>Ambassador</Uni>, as it's typically optimal to wait for noth weapon spread and headshot cooldown to reset before firing again anyway.
    - The <Uni>Ambassador</Uni> only deals 102 damage on headshot, so if being used as an Uber Medic picker, it's important to shoot their target in order to deal 150 damage to the pocket.

<!--### Secondary -->
<!--### Melee-->

<h3 id="spy_pda2">PDA2</h3>

- Unstable Mod: Cash Vacuum
  - <Pos>+400% credit collection radius on wearer</Pos>
  - <Pos>Gain +40 health from collected credits</Pos>
  - Available on:
    - <Nor>Invis Watch</Nor>
    - <Uni>Cloak and Dagger</Uni>
  - Notes:
    - <Pos>+40 health from collected credits</Pos> is capable of providing uncapped overheal.
    - <Pos>+400% credit collection radius on wearer</Pos> is equivalent to Scout's collection range.

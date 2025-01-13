# Spells for the Modpack
This file just contains ideas for spells that I want to add to the modpack. They will be catagorized based on the school they are a part of. I will give the gist of the themes of the spells, I may not follow them super closely just so there is more variety of spells.

Terms to note:
- DMG: normal damage.
- M-DMG: magic damage, pierces armor.
- HP: health, health points.
- ISS: no, not International Space Station; Iron's Spells & Spellbooks

Additional notes:
- The spell rarity system has been changed:
  - **Common → Common**
  - **Uncommon → Rare**
  - **Rare → Epic**
  - **Epic → Legendary**
  - **Legendary → Flawless!**
- Again, no spell leveling.

## Physical
Physical spells usually have to do with affecting a physical action of the player (ie. a stomp, punch, swipe/slash?), physically affecting terrain, forming physical barriers, or direct contact with something. Can also be associated with summoning storms and such.

<details><summary><b><ins>Stomp</ins></b></summary>

*A basic spell that does good damage in melee range.*
```
Stats:
- long cast
- 0.5s cast time
- 10s cooldown
- 2 arcana cost
- common

Info:
- Functions similarly to the stomp spell in base ISS.
- Does 8DMG.
- Increasing spell effectiveness increases DMG.
```
</details>

<details><summary><b><ins>Greater Stomp</ins></b></summary>

*A basic spell that does great damage in melee range.*
```
Stats:
- long cast
- 0.6s cast time
- 12s cooldown
- 5 arcana cost
- rare

Info:
- Functions similarly to the (lesser) Stomp spell, just with a greater cone of effect (hitbox).
- Does 12DMG.
- Increasing spell effectiveness increases DMG.
```
</details>

<details><summary><b><ins>Petrification</ins></b></summary>

*A fairly complex spell that turns the caster into stone.*
```
Stats:
- instant cast
- 20s cooldown
- 2 arcana cost
- rare

Info:
- Adds downwards velocity to the caster.
- Gives the caster the Petrified effect for 10s.
  - Entities with the Petrified effect are given increased gravity, an inability to move, and are immune to damage.
  - Any fall damage that would be taken while under the effect is applied to all entities in a 1.5 block radius around the affected entity.
- Increasing spell effectiveness increases the amount of time Petrified.
```
</details>

<details><summary><b><ins>Slash</ins></b></summary>

*A basic spell that imbues the caster's weapon with the **Physical** magics.*
```
Stats:
- instant cast
- 5s cooldown
- 1 arcana cost
- common

Info:
- Functions similarly to the Flaming Strike spell from base ISS.
- Does 4DMG + the damage attribute of the item you are currently holding.
- Increasing spell effectiveness increases DMG.
```
</details>

<details><summary><b><ins>Greater Slash</ins></b></summary>

*A decent spell that imbues the caster's weapon with a great amount of the **Physical** magics.*
```
Stats:
- long cast
- 0.2 cast time
- 10s cooldown
- 3 arcana cost
- epic

Info:
- Is identical to the (lesser) Slash spell just with a greater area of effect (hitbox).
- Does 6DMG + (1.5x) the damage attribute of the item you are currently holding.
- Increasing spell effectiveness increases DMG.
```
</details>

## Deathly
Deathly spells usually have to do with direct damage or direct healing. Can also be associated with summoning things to fight for you.

<details><summary><b><ins>Healing</ins></b></summary>

*A basic spell used to heal you or a friend.*
```
Stats:
- long cast
- 2s cast time
- 20s cooldown
- 2 arcana cost
- common

Info:
- Heals the caster for 6HP.
- If targeting an entity, heal the entity for 8HP instead. 
- Gives off little green particles when cast.
- Increasing spell effectiveness increases amount of HP healed.
```
</details>

<details><summary><b><ins>Greater Healing</ins></b></summary>

*A decent spell used to heal you or a friend, and provide additional healing over time.*
```
Stats:
- long cast
- 2.5s cast time
- 25s cooldown
- 5 arcana cost
- epic

Info:
- Heals the caster for 8HP and applies Regeneration (I) for 15s.
- If targeting an entity, heal the entity for 10HP and apply Regeneration (I) for 20s instead.
- Gives off larger green particles when cast.
- Increasing spell effectiveness increases amount of HP healed.
```
</details>

<details><summary><b><ins>Hurting</ins></b></summary>

*A basic spell that casts a bolt of hurting.*
```
Stats:
- instant cast
- 5s cooldown
- 1 arcana cost
- common

Info:
- Fires off a magic bolt that flies at a similar tragectory as an arrow.
- Deals 6DMG on contact with an entity.
- Dissapates on contact with a surface or an entity.
- Is affected by Guiding.
- Increasing spell effectiveness increases damage.
```
</details>

<details><summary><b><ins>Greater Hurting</ins></b></summary>

*A decent spell that casts a fast moving bolt of hurting.*
```
Stats:
- instant cast
- 7.5s cooldown
- 3 arcana cost
- rare

Info:
- Fires off a magic bolt that flies at a similar tragectory as an arrow, but way faster.
- Deals 10DMG on contact with an entity.
- Dissapates on contact with a surface or an entity.
- Is affected by Guiding.
- Increasing spell effectiveness increases DMG.
```
</details>

<details><summary><b><ins>Heal Pylon</ins></b></summary>

*A more complex spell used to make a target into a healing field.*
```
Stats:
- long cast
- 15s cast time
- 1hr cooldown
- 10 arcana cost
- epic

Info:
- Cannot be cast without a target entity.
  - Cannot target another player.
- When cast, apply the Healing Pylon effect to the target for 1hr.
  - Healing Pylon makes the affected entity heal all nearby targets for 2HP every second.
- Increasing spell effectiveness increases effect time.
```
</details>

## Emotional
Emotional spells usually have to do with support. Like applying a buff to a friend, and applying a negative effect to a foe.

<details><summary><b><ins>Strengthen</ins></b></summary>

*A basic spell used imbue a target with power.*
```
Stats:
- long cast
- 0.5s cast time
- 30s cooldown
- 2 arcana cost
- rare

Info:
- Gives the caster the Strength (I) effect for 20s.
- If targeting an entity, give the entity the Strength (II) effect for 20s instead.
- Increasing spell effectiveness increases effect time.
```
</details>

<details><summary><b><ins>Snap</ins></b></summary>

*A basic spell used to make a target more vulnerable to attacks.*
```
Stats:
- instant cast
- 30s cooldown
- 2 arcana cost
- rare

Info:
- Casts a hitscan shot that does no damage and has a 30 block range and is blocked by terrain and entities.
- On hit with an entity:
  - Apply Weakness (I), Slowness (I), and Guiding to the entity for 15s.
- Increasing spell effectiveness increases effect time.
```
</details>

<details><summary><b><ins>Greater Snap</ins></b></summary>

*A decent spell used to cripple a target in combat, making them weak.*
```
Stats:
- instant cast
- 30s cooldown
- 5 arcana cost
- epic

Info:
- Casts a hitscan shot that does no damage and has a 45 block range and is blocked by terrain and entities.
- On hit with an entity:
  - Apply Weakness (II), Slowness (I), Blindness, and Guiding to the entity for 20s.
- Increasing spell effectiveness increases effect time.
```
</details>

<details><summary><b><ins>Inspiration</ins></b></summary>

*Inspires nearby entities.*
```
Stats:
- instant cast
- 20s cooldown
- 3 arcana cost
- incremental
- 5 charges
- 10s downtime
- epic

Info:
- Casts a hitscan shot that has a 30 block range and gives any entity that it hits the Inspiration effect.
  - Inspiration gives a 20% speed bonus.
- Increasing spell effectiveness increases effect time.
```
</details>

## Orderly
Orderly spells usually have to do with some sort of imbuement, or maybe telekinesis. In the same vein as **Physical** magic, or complementary to it in a way.

<details><summary><b><ins>Gust</ins></b></summary>

*A basic spell used to launch you a short distance.*
```
Stats:
- instant cast
- 10s cooldown
- 1 arcana cost
- common

Info:
- Adds velocity to the caster in the direction they are looking at.
- Pushes away any entities near the caster by a little bit.
- Increasing spell effectiveness increases velocity.
```
</details>

<details><summary><b><ins>Greater Gust</ins></b></summary>

*A complex spell used to push targets away.*
```
Stats:
- instant cast
- 20s cooldown
- 3 arcana cost
- incremental
- 5 charges
- 7s downtime
- epic

Info:
- Pushes the caster back a little bit when cast.
- Pushes all entities in a cone in front of the caster back a lot.
- Increasing spell effectiveness increases push force.
```
</details>

<details><summary><b><ins>Moonshot</ins></b></summary>

*A complex spell used to launch targets an absurd distance.*
```
Stats:
- long cast
- 1s cast time
- 20s cooldown
- 2 arcana cost
- epic

Info:
- Cannot be cast without a target entity.
- Adds a bunch of velocity to the entity the caster is targeting, sending them in the direction the caster is facing.
- Target entity is made Airborne for 10s.
- Gives the caster a strong movement speed penalty while being cast.
- Increasing spell effectiveness increases velocity.
```
</details>

<details><summary><b><ins>Homebringer</ins></b></summary>

*A neat little spell to teleport a target to you.*
```
Stats:
- instant cast
- 15s cooldown
- 3 arcana cost
- epic

Info:
- Casts a hitscan shot that has a 30 block range and makes any entity that it hits teleport to the caster.
- Increasing spell effectiveness increases range.
```
</details>

<details><summary><b><ins>Tether</ins></b></summary>

*An absurdly complex spell used to tether you to a target, binding your body and soul to them.*
```
Stats:
- long cast
- 2s cast time
- 2m cooldown
- 8 arcana cost
- legendary

Info:
- Cannot be cast without a target entity.
- Gives the caster and the target the effect "Tethered" for 1m.
  - Tethered entities will share any damage they recieve, divided by the amount of tethered entities.
    - X = A / B; where A is the initial damage that would be applied to an entity with the Tethered effect, B is the amount of entities with the Tethered effect, and X is the damage all entities with the Tethered effect would recieve.
- Increasing spell effectiveness increases effect time.
```
</details>

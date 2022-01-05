---
tags: trait, dionysus, presumably_functional
title: ShieldLoadAmmo_DionysusRangedTrait
---
<!-- end front matter -->
# ShieldLoadAmmo_DionysusRangedTrait 
![](../icons/BoonIcons/Dionysus_02_Large.png)

## Helptext
> **Trippy Flare**
> 
> Your **Cast** damages foes around you, leaving behind **Festive Fog**.  
> Blast Damage: **100**/**120**/**140**/**160**

## My Two Cents
> this may look a little familiar - that's because it is! getting dionysus' Trippy Flare is totally natural in-game, but you're not actually getting this trait. instead, you're getting his normal `DionysusRangedTrait`, which has a `TraitDependencyTextOverrides` field that changes the helptext when you have the Beowulf aspect!  
> 
> in fact, it's even in the loot tables for poseidon - but, this trait has a `Skip` field set to `true`. there's only [one other trait with this field](ShieldLoadAmmo_PoseidonRangedTrait), but quite a few elements of removed early-access content have this value. when such an element is considered by the game, this field tells the game to literally skip it and try another option!

## Notes
* **Source:** Dionysus
* **Functional:** presumably
* **See Also:** [`ShieldLoadAmmo_PoseidonRangedTrait`](ShieldLoadAmmo_PoseidonRangedTrait.md)

---
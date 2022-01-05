---
tags: trait, poseidon, presumably_functional
title: "Flood Flare"
---
<!-- end front matter -->
# Flood Flare 
![](BoonIcons/Poseidon_02_Large.png)

---
## Helptext
> **Flood Flare**
> 
> Your **Cast** damages foes around you and knocks them away.  
> Blast Damage: **60**/**90**/**120**/**150**

## My Two Cents
> this may look a little familiar - that's because it is! getting poseidon's Flood Flare is totally natural in-game, but you're not actually getting this trait. instead, you're getting his normal `PoseidonRangedTrait`, which has a `TraitDependencyTextOverrides` field that changes the helptext when you have the Beowulf aspect!  
> 
> in fact, it's even in the loot tables for poseidon - but, this trait has a `Skip` field set to `true`. there's only [one other trait with this field](ShieldLoadAmmo_DionysusRangedTrait), but quite a few elements of removed early-access content have this value. when such an element is considered by the game, this field tells the game to literally skip it and try another option!

## Notes
* **Source:** Poseidon
* **Functional:** presumably
* **See Also:** [`ShieldLoadAmmo_DionysusRangedTrait`](ShieldLoadAmmo_DionysusRangedTrait.md)

---
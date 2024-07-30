# Planning and notes

## Factions

- civil early-industrial faction
  - individualist ideo
  - blue and grey colorsets
- warlike early-industrial faction
  - loyalist
  - red and black color sets

## Military

- base attire
  - Shirt and waistcoat
  - Pants
  - Military boots if available
- infantry
  - officer
    - bicorn hat
    - sabre
    - flintlock pistol
    - ?combat command enabled??
  - line infantry
    - flintlock musket w/bayonet
    - colored jacket, white facings
    - line infantry webbing
    - backpack?
    - low chance to spawn drunk?
  - skirmisher
    - flintlock rifle
    - sword bayonet
    - different colored jacket, maybe forced green?, white facings
    - light infantry webbing
  - engineer and/or grenadier
    - hand bombard
    - demo charges?
    - Engineer webbing
- cavalry
  - dragoons
    - fancy helmet
    - sabre
    - flintlock pistol, carbine musket, or blunderbuss
    - cuirass
    - light infantry webbing
  - lancer
    - Fancy helm
    - lance
    - cuirass
    - light infantry webbing
- mercenary (accompanies traders)
  - Halberd
  - Fancy helmet
  - Cuirass
  - Flintlock pistol or Blunderbuss
  - engineer webbing

## Civilians

- nobles
- merchants
  - Top hat
  - Formal shirt
  - Formal vest
  - Pants
  - ??cape??
  - Shoes
- commoners?

## Traders

- Bulk goods
- Weapons
- ???
- One or two merchants, plus mercenaries

## choose weapon/apparel dependencies

- flintlocks expanded
- redcoats
- supported extras
  - ??

- base on simple industrial faction

## Wishlist

- scale difficulty by upgrading to bolt action

## Code notes

possible drug-use attach, have non-elites arrive drunk?

```xml
    <techHediffsMoney>1000~1200</techHediffsMoney>
    <techHediffsTags>
      <li>Advanced</li>
      <li>ImplantEmpireCommon</li>
    </techHediffsTags>
    <techHediffsChance>0.35</techHediffsChance>
```

> maybe `<startingHediffs>`?
^ maybe only 1.5?

### forced defs

#### grooming standards

> interesting that you can use `HairDef  <forcedHair> in pawnkinddef`

#### more pawnkind defs

> There's also these in pawnkind defs, could be useful for victorian armies:

```C#
        public Color apparelColor = Color.white;
        public QualityCategory itemQuality = QualityCategory.Normal;
        public QualityCategory? forceWeaponQuality;
        public bool forceNormalGearQuality;
        public Gender? fixedGender;
```

#### faction color defs

```xml
    <colorSpectrum>
      <li>(0.03, 0.47, 0.16)</li>
      <li>(0.49, 0.96, 0.51)</li>
    </colorSpectrum>
```
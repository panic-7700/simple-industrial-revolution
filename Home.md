Rough plans

## Military
- base attire
  - Shirt and waistcoat
  - Pants
  - Military boots if available
- officer
  - bicorn hat
  - sabre
  - flintlock pistol
  - ?combat command enabled??
- infantry
  - flintlock musket w/bayonet
  - colored jacket, white facings
  - line infantry webbing
  - low chance to spawn drunk?
- skirmisher
  - flintlock rifle
  - sword bayonet
  - different colored jacket, maybe forced green?, white facings
  - light infantry webbing 
- cavalry / dragoons
  - fancy helmet
  - sabre
  - flintlock pistol, carbine musket, or blunderbuss
  - cuirass
  - light infantry webbing
- lancer
  - Fancy helm
  - lance
  - cuirass
- Mercenary
  - Halberd
  - Fancy helmet
  - Cuirass
  - Flintlock pistol or Blunderbuss
- Engineer
  - hand bombard
  - demo charges?
  - Engineer webbing
- Grenadier

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

possible drug-use attach
    <techHediffsMoney>1000~1200</techHediffsMoney>
    <techHediffsTags>
      <li>Advanced</li>
      <li>ImplantEmpireCommon</li>
    </techHediffsTags>
    <techHediffsChance>0.35</techHediffsChance>
> maybe <startingHediffs>? 
^ maybe only 1.5?


>  interesting that you can use HairDef  <forcedHair> in pawnkinddef 

> There's also these in pawnkind defs, could be useful for victorian armies:
        public Color apparelColor = Color.white;
        public QualityCategory itemQuality = QualityCategory.Normal;
        public QualityCategory? forceWeaponQuality;
        public bool forceNormalGearQuality;
        public Gender? fixedGender;


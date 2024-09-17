# Planning and notes


## Factions

- just two to keep it simple
- no permanently hostile factions because Reasons
	- but maybe make it so they're harder to keep happy
- revolutionary early-industrial faction
	- individualist ideo
	- blue and grey colorsets
- expansionist early-industrial faction
	- loyalist
	- red and black color sets
- stretch goals
	- hire mercenaries
	- title system?
	- rather than drops, trigger caravans?


## Military

- Base attire
	- Shirt and waistcoat
	- Pants
	- Military boots if available
- Infantry
	- Officer
		- bicorn hat
		- sabre
		- flintlock pistol
		- ?combat command enabled?? -- this doesn't seem to be possible unfortunately
	- Line infantry
		- flintlock musket w/bayonet
		- colored jacket, white facings
		- line infantry webbing
		- backpack?
		- low chance to spawn drunk?
		- Elites:
			- Chosen Man (expansionist)
			- Old Guard (revolutionary)
	- Engineer and/or grenadier
		- hand bombard
		- demo charges?
		- Engineer webbing
	- Rifleman
		- **unique to expansionist faction**
		- flintlock rifle
		- sword bayonet
		- different colored jacket, maybe forced green?, white facings
		- light infantry webbing
- Cavalry
	- dragoons
		- fancy helmet
		- sabre
		- flintlock pistol, carbine musket, or blunderbuss
		- cuirass
		- light infantry webbing
	- lancer
		- **unique to revolutionary faction**
		- Fancy helm
		- lance
		- cuirass
		- light infantry webbing
- mercenary
	- **only appears with caravans**
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
- tastier pike and shot?
- supported extras
	- ??

- base on simple industrial faction


## Wishlist

- scale difficulty by upgrading to bolt action
	- martini-henry
	- needle gun


## Code notes

possible drug-use attach, have non-elites occasionally arrive drunk?

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

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
	- Shirt and waistcoat (`redcoats!`)
	- footwear
		- Military boots if available	(`boots and stuff`)
		- boots (`vanilla apparel`)
	- backpack? (except officer)
- Infantry
	- Officer
		- bicorn hat (`redcoats!`)
		- sabre
		- flintlock pistol (`flintlocks`)
		- combat command knockoff (stretch goal)
	- Line infantry
		- flintlock musket w/bayonet (`flintlocks`)
		- colored jacket, white facings (`redcoats!`)
		- line infantry webbing (`redcoats!`)
		- low chance to spawn drunk?
		- Grenadier
			- **unique to revolutionary faction**
			- Bursting and incendiary bombs (`flintlocks`)
			- Grenadier webbing (`redcoats!`)
			- Elites: Old Guard
	- Rifleman
		- **unique to expansionist faction**
		- flintlock rifle (`flintlocks`)
		- sword bayonet
		- different colored jacket, maybe forced green?, white facings (`redcoats!`)
		- light infantry webbing (`redcoats!`)
		- Elites: Chosen Man
- Cavalry
	- dragoons
		- fancy helmet
		- sabre
		- flintlock pistol, carbine musket, or blunderbuss (`flintlocks`)
		- cuirass
		- light infantry webbing (`redcoats!`)
	- lancer
		- Fancy helm
		- lance
		- cuirass
		- light infantry webbing (`redcoats!`)
- mercenary
	- **only appears with caravans**
	- Halberd
	- Fancy helmet
	- Cuirass
	- Flintlock pistol or blunderbuss (`flintlocks`)
	- engineer webbing (`redcoats!`)


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


## Wishlist

- scale difficulty by upgrading to bolt action
	- martini-henry
	- needle gun
- combat command knockoff
	- buff to nearby soldiers
	- reduce suppression chance (CE)
	- increase fire rate


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

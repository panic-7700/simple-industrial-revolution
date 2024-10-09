# Resources


## Code notes

- possible drug-use attach, have non-elites occasionally arrive drunk?

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

- for the _faction_ color, not the ideo or apparel
- [glorious normalized rgb decimal convertor](https://doc.instantreality.org/tools/color_calculator/)

```xml
	<colorSpectrum>
		<li>(0.03, 0.47, 0.16)</li>
		<li>(0.49, 0.96, 0.51)</li>
	</colorSpectrum>
```


## Materials


### Wool

- Alpaca Wool - `WoolAlpaca`
- Bison Wool - `WoolBison`
- Megasloth Wool - `WoolMegasloth`
- Muffalo Wool - `WoolMuffalo`
- Sheep Wool - `WoolSheep`


### Leather

- Bearskin - `Leather_Bear`
- Birdskin - `Leather_Bird`
- Bluefur - `Leather_Bluefur`
- Camelhide - `Leather_Camel`
- Chinchilla Fur - `Leather_Chinchilla`
- Dog Leather - `Leather_Dog`
- Elephant Leather - `Leather_Elephant`
- Foxfur - `Leather_Fox`
- Guinea Pig Fur - `Leather_Guineapig`
- Heavy Fur - `Leather_Heavy`
- Human Leather - `Leather_Human`
- Lightleather - `Leather_Light`
- Lizardskin - `Leather_Lizard`
- Panthera Fur - `Leather_Panthera`
- Patchleather - `Leather_Patch`
- Pigskin - `Leather_Pig`
- Plainleather - `Leather_Plain`
- Rhinoceros Leather - `Leather_Rhinoceros`
- Thrumbofur - `Leather_Thrumbo`
- Wolfskin - `Leather_Wolf`


### Cloth

- Cloth - `Cloth`
- Devilstrand - `DevilstrandCloth`
- Hyperweave - `Hyperweave`
- Synthread - `Synthread`


### Blocks

- Granite - `BlocksGranite`
- Limestone - `BlocksLimestone`
- Marble - `BlocksMarble`
- Sandstone - `BlocksSandstone`
- Slate - `BlocksSlate`


### Metals (and Wood)

- Gold - `Gold`
- Jade - `Jade`
- Plasteel - `Plasteel`
- Silver - `Silver`
- Steel - `Steel`
- Uranium - `Uranium`
- Wood - `WoodLog`

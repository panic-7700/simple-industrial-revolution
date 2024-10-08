# Planning and notes


## Workflow


### 1.0

1. [x] Basic infantry defs
2. [x] Basic faction def for testing
3. [x] Colors and mats
4. [ ] More infantry
	- [x] officers
	- [x] skirmishers
	- [x] mercenaries
	- [TODO] grenadiers
5. [x] ~~Cavalry with giddy up~~
6. [ ] Traders
	- [TODO] nail down shopping list / wares
	- [FIXME] apparel and weapons for merchants and villagers
7. [FIXME] raid balancing needs tuning

#### Testing

- [ ] without CE
- [ ] with CE
- [ ] without any DLC
- [ ] without dependencies
- [ ] at various difficulty settings


### 1.5 / stretch goals

1. Titles
	- Trade discounts?
	- Negative goodwill from factional opponent
	- Permits
		- caravans rather than drops
2. Mechanics
	- Combat Command knockoff for Officers
3. Units
	- Mercenaries hirable by player
	- Elites (excluding line infantry)
4. Tech tree traversal
	- simulated by higher-cost elites with breechloaders or early multishot firearms
	- Martini Henry, Needle, etc (bolt-action for vanilla?)


## Factions

- just two to keep it simple
- no permanently hostile factions because Reasons
	- [TODO] but maybe make it so they're harder to keep happy
- revolutionary early-industrial faction
	- individualist ideo
	- blue ~~and grey~~ color sets
- expansionist early-industrial faction
	- loyalist
	- red ~~and black~~ color sets


## Military

- [ ] Base attire
	- [x] Shirt and waistcoat (`redcoats!`)
	- [ ] footwear
		- boots if available (`redcoats!`, planned)
	- [ ] backpack? (except officer)
- [ ] Infantry
	- [ ] Officer
		- [x] bicorn hat (`redcoats!`)
		- [ ] officer sword (rapier picked from pike & shot?)
		- [x] flintlock pistol (`flintlocks`)
	- [ ] Line infantry
		- [x] flintlock musket w/bayonet (`flintlocks`)
		- [x] colored jacket, white facings (`redcoats!`)
		- [x] line infantry webbing (`redcoats!`)
	- [ ] Grenadier
		- [ ] Bursting and incendiary bombs (`flintlocks`)
		- [x] Grenadier webbing (`redcoats!`)
		- [ ] Elites: Old Guard
	- [ ] Skirmisher
		- [ ] Rifleman **unique to expansionist faction**
			- [x] flintlock rifle (`flintlocks`)
			- [ ] sword bayonet or knife
			- [x] different colored jacket, maybe forced green?, white facings (`redcoats!`)
			- [ ] Elites: Chosen Man
		- [x] light infantry webbing (`redcoats!`)
		- [x] Voltigeur **unique to revolutionary**
			- [x] musket
	- [x] mercenary
		- [x] **mostly appears with caravans**
		- [x] Halberd (picked out of pike & shot)
		- [x] Fancy ~~helmet~~ hat
		- [x] Cuirass (Light Cuirass picked out of pike & shot?)
		- [x] Flintlock pistol or blunderbuss (`flintlocks`)
		- [x] Grenadier webbing (`redcoats!`)
- Stretch goals
	- line infantry
		- low chance to spawn drunk? higher for reserves?
	- officer
		- combat command knockoff (stretch goal)
	- drummer? (stretch goal)
		- boosts or adds combat command knockoff somehow
	- Cavalry
		- on hold pending better understanding of GiddyUp configs
		- dragoon
			- light ranged cavalry w/carbine and sword. originally fought on foot. could still exist if giddyup doesn't work out.
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

- Buy
	- Spices if they exist
	- Chocolate
	- Coffee
	- Tea
	- Cloth
	- Herbal meds
	- Chemfuel
	- Furs (not leathers)
	- Gold
	- Silver
	- Slaves (only expansionist)
- Sell
	- components
	- weapons
- One or two merchants, plus mercenaries
- Will also trade honor for the things they buy


## choose weapon/apparel dependencies

- dependencies
	- flintlocks expanded
	- redcoats
- supported extras
	- CE (for now)
	- Ideo
	- Royalty
	- ??


## Wishlist

- scale difficulty by upgrading to bolt action
	- martini-henry
	- needle gun
- combat command knockoff
	- buff to raid soldiers
	- reduce suppression chance (CE)
	- increase fire rate

### combat command notes

[14:09]shit got me lookin like: Oh god....proximity hediff....
[14:09]panic: probably super expensive so yeah idk
[14:09]panic: it's a wishlist item
[14:09]shit got me lookin like: That will not run well
[14:10]panic: lol
[14:10]panic: yeah
[14:10]panic: maybe just a debuff when the officer is killed
[14:10]shit got me lookin like: Maybe apply a hediff to all other pawns if they spawn in the raid somehow?
[14:10]panic: or that
[14:10]panic: i like that actually
[14:10]panic: neutralize it or malus if they are killed
[14:10]shit got me lookin like: Yeah because you never want proximity shit
[14:10]panic: right
[14:10]panic: i would want it to apply to the whole raid anyway
[14:10]shit got me lookin like: And having them break when the officer is killed so they can route
[14:10]panic: proximity is just where i went thinking about combat command
[14:10]panic: yep
[14:10]panic: exactly
[14:11]panic: or some percentage of them get flee
[14:11]shit got me lookin like: Real
[14:11]panic: and others just reduced effectiveness
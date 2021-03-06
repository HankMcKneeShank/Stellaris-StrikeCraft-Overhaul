# Detailed list of Changes I made

### /common/:

#### /component_sets/:

* Added needed GFX information into the <00_strike_craft.txt>

#### /component_templates/:

* 00_strike_craft.txt :
* Improved readability and fast access to new variables
* Increased **regeneration** from 0.13 to 0.1429 ( Now its actual 8 ingame days per new ship )
* Increased **attackrange** of bombers from 8 to 15 / of fighters from 8 to 15
* Decreased fighter **launch time** from 1.5 to 1.0
* Increased Bomber **speed** from 300/350/400 to 375/425/475
* Increased fighter **speed** from 300/350/400 to 425/475/525
* Increased **rotationspeed** of bombers from 0.1 to 0.25 _(Huge difference in performance!)_ / of fighters from 0.1 to 0.215
* Changed **attackspeed** of bombers from 2 to 4 / of fighters from 2 to 1
* Increased **Bomber Count** from 8 to 12
* Increased **Fighter Counte** from 8 to 10

#### Strike Craft:

* **Acceleration** increased from 0.5 to 1
* **GFX** for all Vessels updated (Hopefully you will see it as improvement)
* **Damage** adjusted , Tier1/Tier2/Tier3 are now semi-equivalent in performance L slots :
* Tier 1 can be compared to a (kinetic battery - ~ 25% damage) @ vesselcount of 10
* Tier 2 can be compared to a (kinetic battery + ~ 8% damage) @ vesselcount of 10
* Tier 3 can be compared to a (Kinetic Artillery + ~ 10% damage) @ vesselcount of 10

!! **(Also compareable to other L slots , K.A. is just used as an example)** !!

#### Fighters:

* **Acceleration** increased from 0.5 to 1
* **Damage** values as follows:
* Tier 1 fighter kills a T1 bomber in about 2 Ingame days
* Tier 2 fighter kills a T2 bomber in about 2 Ingame Days
* Tier 3 fighter kills a T3 Bomber in about 2-3 Ingame Days
* **Attackable Targets** for fighters are as follows : Starbases , Fleet , Missles , Strikecraft , Fighters

#### /ship_behaviors/:

* **Disclaimer** Vessels engage only once fleet is in a Fight , thus cannot be sent out across the galaxy! I tried :C
* All Vessels now have a **engagement range** of 300 ( __returnrange__ @ 310)
* Fighters will **charge into the middle of combat** and form a defensive poke lineup

#### /technology/:

* Starter Vessel Technology __(Carrier Operations)__ now unlocks fighters Tier 1 as well
* Carrier Operations is now a __Tier 2 Tech__ with the **cost** of 1500 and **weight** of 85

* **_Strikecraft Technology adjusted to_** :
  * Tier 2 is now a __Tier 3 Tech__ with the **cost** of 6000 and **weight** of 50
  * Tier 3 is now a __Tier 4 Tech__ with the **cost** of 10000 and **weight** of 40

* **_Fighter Technology costs are_** :
  * Tier 2 is a __Tier 2 Tech__ with the **cost** of 2500 and **weight** of 70
  * Tier 3 is a __Tier 4 Tech__ with the **cost** of 8000 and **weight** of 45
  * Voidcraft AI should prefer to tech into this Technology , just like they do in Strikecraft

### /gfx/:

* Added new icons for the Fighters

### /interface/:

* Added fighter GFX information

### /localisation/:

* Added descriptions for the Fighters itself and their Techs

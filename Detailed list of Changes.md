#Detailed list of Changes I made

### /common/: 

#### /component_sets/: 
  * Added needed GFX information into the <00_strike_craft.txt>

#### /component_templates/:
  * 00_strike_craft.txt :
    * Improved readability and fast access to new variables
    * Increased **attackrange** of bombers from 8 to 10 / of fighters from 8 to 8.5
    * Decreased fighter **launch time** from 1.5 to 1.0
    * Increased fighter **speed** from 300/350/400 to 350/400/450
    * Increased **rotationspeed** of bombers from 0.1 to 0.2 _(Huge difference in performance!)_ / of fighters from 0.1 to 0.215
    * Increased **attackspeed** of bombers from 2 to 3.26 / of fighters from 2 to 0.5
    * Increased **Vessel Count** from 8 to 10
    
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
       * Tier 1 is compareable to 4x Flak Battery @ vesselcount of 8
       * Tier 2 is compareable to 4x Flak Cannons @ vesselcount of 7-8
       * Tier 2 is compareable to 4x Flak Artillery @ vesselcount of 8
      * **Attackable Targets** are as follows : Starbases , Fleet , Missles , Strikecraft , Fighters

#### /ship_behaviors/:
 * **Disclaimer** Vessels engage only once fleet is in a Fight , thus cannot be sent out across the galaxy! I tried :C
 * All Vessels now have a **engagement range** of 300 ( __returnrange__ @ 310)
 * Fighters will **charge at the enemy** like Strike Craft

#### /technology/:     
       

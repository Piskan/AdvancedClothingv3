# AdvancedClothingv3

### EX CLOTHING AND EX BERTATSTORE EVENTS

**This event checks all the information for the ex_clothingstore and inserts the player's data on the ped, if any.**
**For example, you want to return the player's outfit. You can use this event.**

```
TriggerServerEvent('ex_clothingstore:getinfos')
```



**This event checks all the information for the ex_bertatstore and inserts the player's data on the ped and insert player tattoo , if any.**
**For example, you want to return the player's skin. You can use this event.**

```
TriggerServerEvent('ex_bertatstore:getinfos')
```

**Use this event to check the player tattoo.**

```
TriggerServerEvent('ex_bertatstore:getattooinfo')
```

--------------------------------------------------------------------------------------------------------------------------------------------------------

### SAVE SYSTEMS

**There are 4 skin registration systems to choose from. (esx_skin,qb-clothing,ownsystem, custom)**

#### ESX_SKIN SAVE

```
Config.skinstyle = "esx_skin"
```
**This system writes the purchased products directly to the skin section of the users table.**

<img src="https://i.ibb.co/5vMBtH7/esx-skin1.png" alt="alt text" width="720" height="280">


#### QB_CLOTHING SAVE

```
Config.skinstyle = "qb-clothing"
```
**This system writes the received data to the skin section in the playerskins table..**

<img src="https://i.ibb.co/YQFnWvH/qb-clothing.png" alt="alt text" width="720" height="280">


#### OWNSYSTEM SAVE

```
Config.skinstyle = "ownsystem"
```
**This system records the incoming data as json with the player id in the folder...**

<img src="https://i.ibb.co/H4x4y6t/ownsystem.png" alt="alt text" >

<img src="https://i.ibb.co/1r4Bbqr/ownsystem2.png" alt="alt text" >




#### CUSTOM SAVE

```
Config.skinstyle = "custom"
```
**If you use a different clothing method with the Custom save system, the information comes into the config....**

<img src="https://i.ibb.co/FzSX575/clothing3.png" alt="alt text" >

--------------------------------------------------------------------------------------------------------------------------------------------------------

### ADD ITEM VIDEO

**Video:**  https://streamable.com/jmv8gv



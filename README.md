# Working-Fivem-Motel-Key-System

Mlo Original Creator AmaruIgnacio On 5 Mods;

https://www.gta5-mods.com/users/AmaruIgnacio

Mlo Editor C.Hollings

Mlo Edited To Work With A Key System Being Able To Have A Key As An Item In Your Inventory Useing Item Authorization.

For Support Or To See Upcoming Projects Go To Our Discord @ https://discord.gg/uJ3u2W7W3e

# Dependencies

<a href="https://github.com/qbcore-framework/qb-core">QBCore</a>
<br>
<br>
<a href="https://github.com/qbcore-framework/qb-doorlock">QB-DoorLock</a>
<br>
<br>
![image](https://github.com/Cameron2131/Working-Fivem-Motel-Key-System/assets/149907059/325f01f9-c03f-4f8b-b2c2-b930a6c90d35)
<br>
<br>
# Installation
<br>
<br>
First Download The File And Drag The Mlo For The Motel In To QB Core Resources Also Make Sure To Ensure Your File In The Server.cfg Shown Below
<br>
QBCoreFramework_BE2D4C.base\resources\[mlo]

![image2](https://github.com/Cameron2131/Working-Fivem-Motel-Key-System/assets/149907059/c61b838e-b7de-463b-b340-51e36a2bacce)
![image3](https://github.com/Cameron2131/Working-Fivem-Motel-Key-System/assets/149907059/def8d1f9-cfcf-4a7f-941e-74133be86cdc)
--------------------------------------------------------------------------------------------------------------------------------------------------------------

<br>
Now Add The Doorlock File To resources\[qb]\qb-doorlock\configs

![image4](https://github.com/Cameron2131/Working-Fivem-Motel-Key-System/assets/149907059/c9d4f8eb-e8f5-4fc3-9c19-35c96e8f4495)
<br>

--------------------------------------------------------------------------------------------------------------------------------------------------------------
Next Add The Image Provided And Add It To Your Inventory 
<br>
![imag6](https://github.com/Cameron2131/Working-Fivem-Motel-Key-System/assets/149907059/7ddf99dc-3310-42bb-9f38-943122ab4b0a)

--------------------------------------------------------------------------------------------------------------------------------------------------------------
<br>
Now Finally Add The Following To Your QB Shared Items Lua

<br>
<br>
motelkey_1  = { name = 'motelkey_1', label = 'Motel Room One', weight = 100, type = 'item', image = 'motelkey_1.png', unique = true, useable = true, shouldClose = true, combinable = nil, description = 'Motel Room 1 Key' },
<br>
<br>

![image 5](https://github.com/Cameron2131/Working-Fivem-Motel-Key-System/assets/149907059/28c25121-4e06-49bf-9627-4dfdad9d355e)

# MAKE SURE TO REMOVE THE QbDoorLock FILE OUT OF THE MLO FOLDER

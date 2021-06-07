

PewPew Hud is a HUD designed for gunner seats and gives gunners the ability to do everything you can do in the boring/buggy Gunner UI, but in 3rd person. 
There are also a few more features like contact indicator and many more. Perfect for Pilot & Gunner combo (remote controller and gunner seat)


-Install- 

Connect from gunner seat to core (core),radar(radar_1),weapons,(weapon_1 etc),switch(contact). then get the "Contact Indicator For PB.json" and paste it into a programming board. 
Link from the programing board to the switch (contact). This board checks the state of the switch. When a ship enters your radar, the switch will activate and the programming board will see this new state and activate the contact indicator. 
This board must be activated with the F key while your using the seat. You can also add light indicators on your ship by connecting a light (verticle L) to the switch (link switch to light) and set it to blinking also setting the desired RGB and flashin intervals.

You can also add a relay, and then the lights if you want up to 10 or more.




-Features-

3rd Person:
Radar , 
Damage Report , 
Weapon Widget , 
Periscope , 
Target Speed ,
Target Distance ,
Target Voxel Mass ,
Target Threat Level,
Target Has: Radar,Engine(not dead),AGG,Rockets.
NSOF report ,
Hit Probablilty ,
Contact Indicator ,






-Hint-
In third person, right click your target and select indentify. Once Identified you can again right click on the target and Engage or unindentify target. Although it is recommended to start each gun manually as making them all fire at once does not do the server any favours and will reult in many misses.





-Break Down-
Damage Report
Displays a UI that shows what is damaged and where. Alt+1/Alt+2 to change views.

Transponder support
Shows friendly ships with the same transponder ID into a seperate widget (Friendly)

Radar:
Shows targets within a 2su range. Right click on a ship in the widget to see the options available.

Weapon Widget:
Ability to load, unload and reload.

Periscope:
Shows targeted ship. (WIP)

Target Speed:
When you have identified a ship the speed will be displayed.

Target Core Size:
When you have identified a ship the size will be displayed.

NSOF report:
Displays in the LUA console any new ship on fields name and core size.

Hit Probablilty:
Once a target is identified this will show you the probability of shots hitting.

Contact Indicator:
Diplays on the HUD and/or lights when a ship enters radar so you dont miss it.








-To-Do List-

Sound Alerts 

Overhaul UI

Chase

Radar enter ship name, currently "unreachable" (that does not crash). On "Ship left" does display name.

Store ship ID's and ship names to DB and display previous ship names in console on radar.enter()




If I ever to publish the full mod, this is the name I picked. 


--MAP.TXT&MISSION.TXT--
Map.txt includes a custom space station that I added although it worked at first glance, it didn't appear after
I modified it a little. And mission.txt has a few dialogueS which are probably sloppy since I'm not really good at 
that sorf of thing. 


--EVENTS.TXT/POWER.TXT--
Events.txt handles the multiple fuel consumption scenarios of different generators together. If you have 2 different
"Diesel Generators" for example, that consumes "4 and 7 fuel canisters" each, normally you need to make 2 different events 
where "Diesel Generator-A" will eat up 4 while "Diesel Generator-B" will eat up "7 fuel canisters" every time you land
and take off. However when you install them both, you need to make a specific event where it requires both as outfits
and will eat up 11 fuel canisters. Otherwise, you will end up consuming 7 for both of the generators. Installing
multiple numbers of the same generator consumes it's double value, **but I'm not sure.** In that case, every ship 
in the game was to be given "Generator Installment Allowance" outfit so that a player may install one generator
at a time. That takes away the ability of installing more than 1 generator of any kind. However in power.txt, only
"Fusion Reactor" requires it since some generators like "Nuclear Fission Reactor MK-I" has more than 2 capacity modifiers.
And an outfit doesn't accept a 3rd one. So I would recommend deleting any modifiers that you don't find fitting.

--NOTES--

In it's most basic form, the generators only produce heat and the fuels have the power generation. Without generators, 
you can't install the fuels and I made the power generation values greater than the vanilla ones since otherwise you 
would have no reason to install them to pay for the fuels. Since generators will consume fuels, every time you land
and take off, your power generation over time will be crippled and you need to manually purchase the corresponding fuels
from the outfit store. I wanted to add a feature where the game asks player to automatically replenish the missing fuel 
canisters/rods when they dock but I'm not sure if possible. And it only works for the "capital ships". Generators can be
installed in the other ships in the fleet, but they won't lose any fuel. My other mod adds it's own "Nuclear Reactors" which
don't require fuel themselves, instead can produce "Nuclear Byproduct" that you can transport to certain locations 
provided by the job that I planned to add. I don't remember if it's working currently and I would recommend not to use
mods at the same time since, certain contents might have the same name.
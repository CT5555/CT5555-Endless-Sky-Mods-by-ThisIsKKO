If I ever to publish the full mod, this is the name I picked. Almost none of them is complete. Includes the FUEL CONSUMING GENERATORS and NUCLEAR WASTE MANAGEMENT & AUTOMATIC MISSILE PRODUCTION. Events are little bit of a mess, so good luck! If you have any questions, I'm on the Endless Sky Discord Server with nickname "ThisIsNotKKO". Everyone is fully authorized to use and modify the codes to be redistributed, however a simple thanks as a sidenote would be appreciated.

-----FUEL CONSUMING GENERATORS MOD-----

--MAP.TXT&MISSION.TXT--
Map.txt includes a custom space station that I added although it worked at first glance, it didn't appear after
I modified it a little. And mission.txt has a few dialogues which are probably sloppy since I'm not really good at 
that sorf of thing. 


--EVENTS.TXT/POWER.TXT--
Events.txt handles the multiple fuel consumption scenarios of different generators alone or together. If you have 2 different
"Diesel Generators" for example, that consumes "4 and 7 fuel canisters" each, normally you need to make 2 different events 
where "Diesel Generator-A" will eat up 4 while "Diesel Generator-B" will eat up "7 fuel canisters" every time you land
and take off. However when you install them both, you need to make a specific event where it requires both as outfits
and will eat up 11 fuel canisters. Otherwise, you will end up consuming total value of 7 for both of the generators. Installing
multiple numbers of the same generator consumes its double value, **but I may not be right.** In that case, every ship 
in the game was to be given "Generator Installment Allowance" outfit so that a player may install one generator
at a time. That takes away the ability of installing more than 1 generator of any kind. However in power.txt, only
"Fusion Reactor" requires it since some generators like "Nuclear Fission Reactor MK-I" has more than 2 capacity modifiers.
And an outfit doesn't accept a 3rd one. So I would recommend deleting any modifiers that you don't find fitting. I also added
certain cooling systems that run on coolants which works with the same principle as the generators.


--SHIPS.TXT/SALES.TXT--
Ships.txt and the other factions txt files add the "Generator Installment Allowance" outfit into every vanilla ship in the game 
in case anyone wants to go for that direction. Sales add the introduced outfits to certain points to be sold.

--NOTES--
In its most basic form, the generators only produce heat and the fuels have the power generation. Without generators, 
you can't install the fuels and I made the power generation values greater than the vanilla ones since otherwise you 
would have no reason to install them to pay for the fuels. Since generators will consume fuels, every time you land
and take off, your power generation over time will be crippled and you need to manually purchase the corresponding fuels
from the outfit store. I wanted to add a feature where the game asks the player to automatically replenish the missing fuel 
canisters/rods when they dock but I'm not sure if it's possible. And it only works for the "capital ships". Generators can be
installed in the other ships in the fleet, but they won't lose any fuel. My other mod adds its own "Nuclear Reactors" which
don't require fuel themselves, instead can produce "Nuclear Byproduct" that you can transport to certain locations 
provided by the job that I planned to add. I don't remember if it's working currently and I would recommend not to use the 2
mods at the same time since, certain contents might have the same name.

-----NUCLEAR WASTE MANAGEMENT & AUTOMATIC MISSILE PRODUCTION-----

--MISSILES.TXT--
Events are included in the same file with the outfits. It works in the same as the Fuel Consuming Generator mods' generators 
but with an extra. Every missile assembler consumes energy and produces heat has its required raw materials that can be purchased as outfits and in return, they add missiles to your ships. Even though the events require only a certain type of raw materials without a certain count to be activated (which means even if you have only 1 Sidewinder Raw Parts, it's gonna kick in), in order to add the missiles, it takes away a number of raw parts more than 1. As I don't fully remember, it may not even take or add anything. If so, 
I recommend reducing the raws taken to -1. It only works for the "capital ship". Other ships won't get their ammunition replenished
or raws taken away. The reason that I made this mod in the first place is that rather than buying missiles, this option ought to 
be more economic and you can sell those missiles for conceviable profits over the costs of the raw materials.


--NUCLEAR.TXT--
Events are included in the same file with the outfits. Nuclear Waste Management's working method is the same as others. Fission Reactors don't require any fuel to consume and just generate "Nuclear Byproducts" which you would be able to transport to certain points provided by the jobs you've accepted to get nuclear warheads. That would probably be sort of an illegal job which would enable you to assemble those warheads into nukes. However I haven't added the anything about Nuclear Warhead other than itself as an outfit, and the only job I added pays you credits for the delivery instead of giving warheads. It's been a while since I tried it, I don't remember if the mission worked. However the waste generation works quite well.


--SALES.TXT/VARIANTS.TXT--
Sales.txt just adds the outfits introduced to the selling points. Variants.txt was supposed to add several merchant vehicles carrying 
warheads on board thay player could plunder and sell or assemble into nukes.



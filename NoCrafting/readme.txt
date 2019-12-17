No Crafting MOD, with QoL
For 7 Days to Die A18

This is a simple mod to use when you want to do a No Crafting playthrough.
Not all files are necessary.

A couple of guys I watch on YouTube have started "no crafting" series, but
inevitably have either accidentally crafted, or confused "no crafting" with
"some crafting", and that kinda got me wanting to write a proper "no crafting"
mod.

It may not be perfect, but it does work acceptably. With that, I say much thanks
to the 7DaystoDie MODs forum, and sphereii specifically for the Xpath thread, which 
I read through (and re-read parts) to figure out using xpath to make a modlet... 
Learn by Doing, amiright...

List of Files, and a brief explanation:

<NO CRAFTING>

quests.xml - This file is important to the "no crafting" mod, unless you just
	skip the starting tutorial quests anyway.. 
	This modification starts your tutorial looking for materials to craft a
	stone axe, then skips directly to the White River Citizen quest to find
	the trader.
		It rewards you with 4 skill points and 700xp. Trader quest grants
		one additional skill point.

recipes.xml - This file is very important to the "no crafting" mod. It removes ALL crafting recipes,
	rendering you literally unable to craft.
		*I had to leave in all the item modification items, i.e. 2xScope,
		Semi-auto trigger, etc., otherwise the trader will sell them for
		0 cost. I'm not sure why it does that, but mitigation for this
		is in the items.xml
	I have also left in the ability to assemble (see what I did there) vehicles
	from parts that you find or buy. (Unless you just like running everywhere..
		I'll leave that to you)

items.xml - This file is also very important to the "no crafting" mod. It allows the mod 
	items to be sold by the trader for a price greater than 0.
		If you want free item mods, remove this file. (Shame on you)
*note: you CAN still buy, or find, wood or rebar frames, and upgrade them normally.. 
	also, you CAN repair items with the proper repair items.

<QoL>

entityclasses.xml -  I have always liked the idea of getting specific items from 
	specific Z drops, so this files adds 8 new loot containers to correspond 
	to 8 of the (vanilla) Zs that you encounter normally.
	For example: the Nurse drops med supplies, Soldier has military items, etc.
	This file is not required for "no crafting" (but helps)
	This file also increases drop rates from .02->.2
	and pokes out the vultures eyes reducing range from 70->7
		You can remove these lines if you don't want that. They are found
		at the top of the list.

loot.xml - This file goes with the entityclasses file to fill those particular
	loot containers with goodies. (I tried to keep it real, not to be too OP)
	This file also contains a line (at the top) which you can remove if you
	like that will destroy any garbage after you loot them. (trash bags, etc.)
		This file is not required for "no crafting", but you must keep it
	if you want the loot distinction described above.


progression.xml - This file is for a solo player to be able to specialize into 
	more than one attribute. It reduces attribute point costs to "1" for each
	level above the vanilla lv5.
		This file is not required for "no crafting"


ENJOY Not Crafting!

		--12pack






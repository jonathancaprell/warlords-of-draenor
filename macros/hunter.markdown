#Dynamic Level 30 Talents

##Macro
--------------------
	#showtooltip
	/cast [talent: 2/1] Binding Shot; [talent: 2/2] Wyvern Sting; [talent: 2/3] Intimidation
	
##Breakdown
--------------------
**`#showtooltip`**

Both the icon and tooltip of this macro are updated dynamically based upon the player’s talent selection in the second tier, defined below.

**`/cast [talent: 2/1] Binding Shot; [talent: 2/2] Wyvern Sting; [talent: 2/3] Intimidation`**

A single ability in the tier—Binding Shot, Wyvern Sting, or Intimidation—is cast with no modification.



#Dynamic Level 60 Talents

##Macro
--------------------
	#showtooltip [talent: 4/1] Fervor; [talent: 4/2] Dire Beast; [talent: 4/3] Thrill of the Hunt
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast [talent: 4/1] Fervor; [talent: 4/2] Dire Beast
	/startattack

##Breakdown
--------------------
**`#showtooltip [talent: 4/1] Fervor; [talent: 4/2] Dire Beast; [talent: 4/3] Thrill of the Hunt`**

Both the icon and tooltip of this macro are updated dynamically based upon the player’s talent selection in the second tier. These are called in specific because Thrill of the Hunt is passive, and elsewise would not return.

**`/cancelaura Hand of Protection`**

If Hand of Protection is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

If the player’s pet does not have a target, the pet is sent to attack the player’s target; elsewise, the 

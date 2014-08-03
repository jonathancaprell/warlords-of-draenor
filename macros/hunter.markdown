#Arcane Shot & Combat Management

##Macro

	#showtooltip
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast Arcane Shot
	/startattack

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (i.e, if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast Arcane Shot`**

[**Arcane Shot**](http://wod.wowhead.com/spell=3044) is cast with no modification.

**`/startattack`**

The player begins (or continues) attacking.



#Aspect of the Cheetah, Toggle Disabled

##Macro

	#showtooltip
	/cast !Aspect of the Cheetah

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/cast !Aspect of the Cheetah`**

[**Aspect of the Cheetah**](http://wod.wowhead.com/spell=5118) is cast, and subsequent casts of this ability will not toggle the aura off if it is still present on the player.



#Bestial Wrath

##Macro

	#showtooltip
	/cancelaura Hand of Protection
	/cast Bestial Wrath

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/cast Bestial Wrath`**

[**Bestial Wrath**](http://wod.wowhead.com/spell=19574) is cast with no modification.



#Black Arrow & Combat Management

##Macro

	#showtooltip
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast Black Arrow
	/startattack

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (i.e, if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast Black Arrow`**

[**Black Arrow**](http://wod.wowhead.com/spell=3674) is cast with no modification.

**`/startattack`**

The player begins (or continues) attacking.



#Chimaera Shot & Combat Management

##Macro

	#showtooltip
	/stopcasting
	/stopcasting
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast Chimaera Shot
	/startattack

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/stopcasting`**

All casting by the player is called to halt.

**`/stopcasting`**

All casting by the player is called to halt. This line is repeated because abilities with a cast time or channel must be halted separately from the player’s white swings.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (i.e, if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast Chimaera Shot`**

[**Chimaera Shot**](http://wod.wowhead.com/spell=53209) is cast with no modification.

**`/startattack`**

The player begins (or resumes) attacking.



#Counter Shot Priority System

##Macro

	#showtooltip
	/stopcasting
	/stopcasting
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast [@mouseover, exists, harm, nodead] [@focus, exists, harm, nodead] Counter Shot; Counter Shot
	/startattack

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/stopcasting`**

All casting by the player is called to halt.

**`/stopcasting`**

All casting by the player is called to halt. This line is repeated because abilities with a cast time or channel must be halted separately from the player’s white swings.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (i.e, if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast [@mouseover, exists, harm, nodead] [@focus, exists, harm, nodead] Counter Shot; Counter Shot`**

If there is a living, hostile mouseover target; or, if there is a living, hostile focused target; or, if there is a living, hostile target selected, [**Counter Shot**](http://wod.wowhead.com/spell=147362) is cast on that target. The macro checks each of these conditions in order, and will cast when the first condition returns true; no ability will be cast if all of these conditions are false.

**`/startattack`**

The player begins (or resumes) attacking.



#Deterrence & Deterrence Cancellation

##Macro

	#showtooltip
	/cancelaura Deterrence
	/cast Deterrence

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/cancelaura Deterrence`**

If [**Deterrence**](http://wod.wowhead.com/spell=19263) is present on the player, the aura is cancelled. This is done so that the player can more quickly resume combat if damage mitigation is no longer required.

**`/cast Deterrence`**

[**Deterrence**](http://wod.wowhead.com/spell=19263) is cast with no modification.



#Draenic Agility Potion & Pet Movement

##Macro

	#showtooltip Draenic Agility Potion
	/cast [nocombat] Dash
	/cast [nocombat] Dive
	/use Draenic Agility Potion

##Breakdown

**`#showtooltip Draenic Agility Potion`**

Both the icon and tooltip of this macro are defined by the item [**Draenic Agility Potion**](http://wod.wowhead.com/item=109217). This is called in specific because other abilities precede the item’s usage in the macro.

**`/cast [nocombat] Dash`**

[**Dash**](http://wod.wowhead.com/spell=61684) is cast if the player is out of combat. This is meant to quick the pet’s initial entry into the encounter, and so is not called if the player is already in combat.

**`/cast [nocombat] Dive`**

[**Dive**](http://wod.wowhead.com/spell=23145) is cast if the player is out of combat. This is meant to quick the pet’s initial entry into the encounter, and so is not called if the player is already in combat.

**`/use Draenic Agility Potion`**

[**Draenic Agility Potion**](http://wod.wowhead.com/item=109217) is used with no modification.



#Dynamic Level 30 Talents

##Macro

	#showtooltip
	/cast [talent: 2/1] Binding Shot; [talent: 2/2] Wyvern Sting; [talent: 2/3] Intimidation
	
##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are updated dynamically based upon the player’s talent selection in the second tier, as defined below.

**`/cast [talent: 2/1] Binding Shot; [talent: 2/2] Wyvern Sting; [talent: 2/3] Intimidation`**

An ability in the tier—[**Binding Shot**](http://wod.wowhead.com/spell=109248), [**Wyvern Sting**](http://wod.wowhead.com/spell=19386), or [**Intimidation**](http://wod.wowhead.com/spell=19577)—is cast based upon the player’s choice in the talent tree.



#Dynamic Level 60 Talents

##Macro

	#showtooltip [talent: 4/1] Fervor; [talent: 4/2] Dire Beast; [talent: 4/3] Thrill of the Hunt
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast [talent: 4/1] Fervor; [talent: 4/2] Dire Beast
	/startattack

##Breakdown

**`#showtooltip [talent: 4/1] Fervor; [talent: 4/2] Dire Beast; [talent: 4/3] Thrill of the Hunt`**

Both the icon and tooltip of this macro are updated dynamically based upon the player’s talent selection in the fourth tier. These choices are called in specific because [**Thrill of Hunt**](http://wod.wowhead.com/spell=109306) is passive, and elsewise would not return.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (i.e, if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast [talent: 4/1] Fervor; [talent: 4/2] Dire Beast`**

An ability in the tier—[**Fervor**](http://wod.wowhead.com/spell=82726) or [**Dire Beast**](http://wod.wowhead.com/spell=120679)—is cast based upon the player’s choice in the talent tree. [**Thrill of Hunt**](http://wod.wowhead.com/spell=109306) is not called, and no ability will be cast if this talent was chosen.

**`/startattack`**

The player begins (or continues) attacking.



#Dynamic Level 75 Talents

##Macro

	#showtooltip [talent: 5/1] A Murder of Crows; [talent: 5/2] Blink Strikes; [talent: 5/3] Stampede
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast [talent: 5/1] A Murder of Crows; [talent: 5/3] Stampede
	/startattack

##Breakdown

**`#showtooltip [talent: 5/1] A Murder of Crows; [talent: 5/2] Blink Strikes; [talent: 5/3] Stampede`**

Both the icon and tooltip of this macro are updated dynamically based upon the player’s talent selection in the fifth tier. These choices are called in specific because [**Blink Strikes**](http://wod.wowhead.com/spell=130392) is passive, and elsewise would not return.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (i.e, if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast [talent: 5/1] A Murder of Crows; [talent: 5/3] Stampede`**

An ability in the tier—[**A Murder of Crows**](http://wod.wowhead.com/spell=131894) or [**Stampede**](http://wod.wowhead.com/spell=121818)—is cast based upon the player’s choice in the talent tree. [**Blink Strikes**](http://wod.wowhead.com/spell=130392) is not called, and no ability will be cast if this talent was chosen.

**`/startattack`**

The player begins (or continues) attacking.



#Dynamic Level 90 Talents

##Macro

	#showtooltip
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists, talent: 6/2] [@pettarget, noexists, talent: 6/3]
	/cast [talent: 6/1] Glaive Toss; [talent: 6/2] Powershot; [talent: 6/3] Barrage
	/startattack [talent: 6/2] [talent: 6/3]

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are updated dynamically based upon the player’s talent selection in the sixth tier, as defined below.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists, talent: 6/2] [@pettarget, noexists, talent: 6/3]`**

The pet begins attacking the player’s target if the pet does not already have a target, and if either [**Powershot**](http://wod.wowhead.com/spell=109259) or [**Barrage**](http://wod.wowhead.com/spell=120360) was taken in the sixth tier; elsewise (i.e, if the pet has a target, or if [**Glaive Toss**](http://wod.wowhead.com/spell=117050) [or no talent] is taken) the pet continues as before. These conditions are set, both so that the pet can remain on a different target than the player’s if previously directed, and so that [**Glaive Toss**](http://wod.wowhead.com/spell=117050) can still be pre-cast before an encounter begins.

**`/cast [talent: 6/1] Glaive Toss; [talent: 6/2] Powershot; [talent: 6/3] Barrage`**

An ability in the tier—[**Glaive Toss**](http://wod.wowhead.com/spell=117050), [**Powershot**](http://wod.wowhead.com/spell=109259), or [**Barrage**](http://wod.wowhead.com/spell=120360)—is cast based upon the player’s choice in the talent tree.

**`/startattack [talent: 6/2] [talent: 6/3]`**

The player begins (or continues) attacking if either [**Powershot**](http://wod.wowhead.com/spell=109259) or [**Barrage**](http://wod.wowhead.com/spell=120360) was taken in the sixth tier. Elsewise, the player continues as before. These conditions are set so that [**Glaive Toss**](http://wod.wowhead.com/spell=117050) can still be pre-cast before an encounter begins.



#Explosive Shot & Combat Management

##Macro

	#showtooltip
	/stopcasting
	/stopcasting
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast Explosive Shot
	/startattack

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/stopcasting`**

All casting by the player is called to halt.

**`/stopcasting`**

All casting by the player is called to halt. This line is repeated because abilities with a cast time or channel must be halted separately from the player’s white swings.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (i.e, if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast Explosive Shot`**

[**Explosive Shot**](http://wod.wowhead.com/spell=53301) is cast with no modification.

**`/startattack`**

The player begins (or resumes) attacking.



#Focus Generator & Combat Management

##Macro

	#showtooltip
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast Steady Shot
	/startattack

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are updated dynamically based upon the player’s specialization and the player’s selection in the seventh talent tier. The details of this are described below.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (i.e, if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast Steady Shot`**

[**Steady Shot**](http://wod.wowhead.com/spell=56641), [**Cobra Shot**](http://wod.wowhead.com/spell=77767), or [**Focusing Shot**](http://wod.wowhead.com/spell=152245) is cast, based upon the player’s specialization and the player’s selection in the seventh talent tier. This happens because of deeper mechanical underpinnings in the game wherein [**Steady Shot**](http://wod.wowhead.com/spell=56641) serves as the least common denominator for all three abilities, triggering whichever focus generator is actually available to the player.

**`/startattack`**

The player begins (or continues) attacking.



#Focus Target Management & Misdirection

##Macro

	#showtooltip Misdirection
	/focus [help]
	/stopmacro [help]
	/cast [@mouseover, exists, help, nodead] [@focus, exists, help, nodead] [@pet, exists, nodead] Misdirection

##Breakdown

**`#showtooltip Misdirection`**

Both the icon and tooltip of this macro are defined by the ability [**Misdirection**](http://wod.wowhead.com/spell=34477). This is called in specific because the macro also serves to define the player’s focus target, wherein the ability is inactive.

**`/focus [help]`**

If the player’s selected target is an ally, then that target is made the player’s focus.

**`/stopmacro [help]`**

If the player’s selected target is an ally, the macro ceases, and no more of it is executed. This allows the macro to define the player’s focus as a targeted ally without immediately casting [**Misdirection**](http://wod.wowhead.com/spell=34477) on that target.

**`/cast [@mouseover, exists, help, nodead] [@focus, exists, help, nodead] [@pet, exists, nodead] Misdirection`**

If there is a living, allied mouseover target; or, if there is a living, allied focused target; or, if the player’s pet exists and is living, then [**Misdirection**](http://wod.wowhead.com/spell=34477) is cast on that target. The macro checks each of these conditions in order, and will cast when the first condition returns true; no ability will be cast if all of these conditions are false.



#Kill Command & Combat Management

##Macro

	#showtooltip
	/stopcasting
	/stopcasting
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast Kill Command
	/startattack

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/stopcasting`**

All casting by the player is called to halt.

**`/stopcasting`**

All casting by the player is called to halt. This line is repeated because abilities with a cast time or channel must be halted separately from the player’s white swings.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (i.e, if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast Kill Command`**

[**Kill Command**](http://wod.wowhead.com/spell=34026) is cast with no modification.

**`/startattack`**

The player begins (or resumes) attacking.



#Kill Shot & Combat Management

##Macro

	#showtooltip
	/stopcasting
	/stopcasting
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast Kill Shot
	/startattack

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/stopcasting`**

All casting by the player is called to halt.

**`/stopcasting`**

All casting by the player is called to halt. This line is repeated because abilities with a cast time or channel must be halted separately from the player’s white swings.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (i.e, if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast Kill Shot`**

[**Kill Shot**](http://wod.wowhead.com/spell=53351) is cast with no modification.

**`/startattack`**

The player begins (or resumes) attacking.



#Master’s Call

##Macro

	#showtooltip
	/cast [@mouseover, exists, help, nodead] [@target, exists, help, nodead] Master's Call; Master's Call

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/cast [@mouseover, exists, help, nodead] [@target, exists, help, nodead] Master's Call; Master's Call`**

If there is a living, allied mouseover target, or, if there is a living, allied focused target, then [**Master's Call**](http://wod.wowhead.com/spell=53271) is cast on that target. The macro checks each of these conditions in order, and will cast when the first condition returns true; if all of these conditions are false, [**Master's Call**](http://wod.wowhead.com/spell=53271) is cast with no modification (i.e, on the player).



#Multi-Shot & Combat Management

##Macro

	#showtooltip
	/stopcasting
	/stopcasting
	/cancelaura Hand of Protection
	/petattack [@pettarget, noexists]
	/cast Multi-Shot
	/startattack

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/stopcasting`**

All casting by the player is called to halt.

**`/stopcasting`**

All casting by the player is called to halt. This line is repeated because abilities with a cast time or channel must be halted separately from the player’s white swings.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/petattack [@pettarget, noexists]`**

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (i.e, if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast Multi-Shot`**

[**Multi-Shot**](http://wod.wowhead.com/spell=2643) is cast with no modification.

**`/startattack`**

The player begins (or resumes) attacking.



#Rapid Fire

##Macro

	#showtooltip
	/cancelaura Hand of Protection
	/cast Rapid Fire

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/cancelaura Hand of Protection`**

If [**Hand of Protection**](http://wod.wowhead.com/spell=1022) is present on the player, the aura is cancelled.

**`/cast Rapid Fire`**

[**Rapid Fire**](http://wod.wowhead.com/spell=3045) is cast with no modification.



#Roar of Sacrifice

##Macro

	#showtooltip
	/cast [@mouseover, exists, help, nodead] [@target, exists, help, nodead] Roar of Sacrifice; Roar of Sacrifice

##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are defined by the ability below.

**`/cast [@mouseover, exists, help, nodead] [@target, exists, help, nodead] Roar of Sacrifice; Roar of Sacrifice`**

If there is a living, allied mouseover target, or, if there is a living, allied focused target, then [**Roar of Sacrifice**](http://wod.wowhead.com/spell=53480) is cast on that target. The macro checks each of these conditions in order, and will cast when the first condition returns true; if all of these conditions are false, [**Roar of Sacrifice**](http://wod.wowhead.com/spell=53480) is cast with no modification (i.e, on the player).

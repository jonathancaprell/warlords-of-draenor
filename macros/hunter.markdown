#Dynamic Level 30 Talents

##Macro

	#showtooltip
	/cast [talent: 2/1] Binding Shot; [talent: 2/2] Wyvern Sting; [talent: 2/3] Intimidation
	
##Breakdown

**`#showtooltip`**

Both the icon and tooltip of this macro are updated dynamically based upon the player’s talent selection in the second tier, as defined below.

**`/cast [talent: 2/1] Binding Shot; [talent: 2/2] Wyvern Sting; [talent: 2/3] Intimidation`**

A single ability in the tier—[**Binding Shot**](http://wod.wowhead.com/spell=109248), [**Wyvern Sting**](http://wod.wowhead.com/spell=19386), or [**Intimidation**](http://wod.wowhead.com/spell=19577)—is cast with no modification.



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

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast [talent: 4/1] Fervor; [talent: 4/2] Dire Beast`**

A single active ability in the tier—[**Fervor**](http://wod.wowhead.com/spell=82726) or [**Dire Beast**](http://wod.wowhead.com/spell=120679)—is cast with no modification. [**Thrill of Hunt**](http://wod.wowhead.com/spell=109306) is not called, and no ability will be cast if this talent was chosen; regardless, all other lines occur.

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

The pet begins attacking the player’s target if the pet does not already have a target; elsewise (if the pet has a target) the pet continues as before. This condition is set so that the pet can remain on a different target than the player’s if previously directed.

**`/cast [talent: 5/1] A Murder of Crows; [talent: 5/3] Stampede`**

A single active ability in the tier—[**A Murder of Crows**](http://wod.wowhead.com/spell=131894) or [**Stampede**](http://wod.wowhead.com/spell=121818)—is cast with no modification. [**Blink Strikes**](http://wod.wowhead.com/spell=130392) is not called, and no ability will be cast if this talent was chosen; regardless, all other lines occur.

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

The pet begins attacking the player’s target if the pet does not already have a target, and if either [**Powershot**](http://wod.wowhead.com/spell=109259) or [**Barrage**](http://wod.wowhead.com/spell=120360) was taken in the sixth tier; elsewise (if the pet has a target, or if [**Glaive Toss**](http://wod.wowhead.com/spell=117050) [or no talent] is taken) the pet continues as before. These conditions are set, both so that the pet can remain on a different target than the player’s if previously directed, and so that [**Glaive Toss**](http://wod.wowhead.com/spell=117050) can still be pre-cast before an encounter begins.

**`/cast [talent: 6/1] Glaive Toss; [talent: 6/2] Powershot; [talent: 6/3] Barrage`**

A single ability in the tier—[**Glaive Toss**](http://wod.wowhead.com/spell=117050), [**Powershot**](http://wod.wowhead.com/spell=109259), or [**Barrage**](http://wod.wowhead.com/spell=120360)—is cast with no modification.

**`/startattack [talent: 6/2] [talent: 6/3]`**

The player begins (or continues) attacking if either [**Powershot**](http://wod.wowhead.com/spell=109259) or [**Barrage**](http://wod.wowhead.com/spell=120360) was taken in the sixth tier. Elsewise, the player continues as before. These conditions are set so that [**Glaive Toss**](http://wod.wowhead.com/spell=117050) can still be pre-cast before an encounter begins.

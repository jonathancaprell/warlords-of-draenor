##Dynamic Level 30 Talents

```
#showtooltip
/cast [talent: 2/1] Binding Shot; [talent: 2/2] Wyvern Sting; [talent: 2/3] Intimidation
```

###Breakdown

**```#showtooltip```**

Both the icon and tooltip of this macro are updated dynamically based upon the player’s talent selection in the second tier.

**```/cast [talent: 2/1] Binding Shot; [talent: 2/2] Wyvern Sting; [talent: 2/3] Intimidation```**

A single ability in the tier, defined by the previous talent choice—Binding Shot, Wyvern Sting, or Intimidation—is cast with no modification.

###Dynamic Level 60 Talents

```
#showtooltip [talent: 4/1] Fervor; [talent: 4/2] Dire Beast; [talent: 4/3] Thrill of the Hunt
/cancelaura Hand of Protection
/petattack [@pettarget, noexists]
/cast [talent: 4/1] Fervor; [talent: 4/2] Dire Beast
/startattack
```

**```#showtooltip```**

Both the icon and tooltip of this macro are updated dynamically based upon the player’s talent selection in the fourth tier. The abilities are called in specific because Thrill of the Hunt is a passive, and would elsewise not return.

**```/cancelaura Hand of Protection```**

If Hand of Protection is present, the aura is cancelled.

**```/petattack [@pettarget, noexists]```**

If the player’s pet does not have a target, the pet is sent to attack the player’s target; elsewise, 
A single ability in the tier, defined by the previous talent choice—Binding Shot, Wyvern Sting, or Intimidation—is cast with no modification.

#Dynamic Level 75 Talents + HoP Cancellation + Combat Maintenance
```
#showtooltip [talent: 5/1] A Murder of Crows; [talent: 5/2] Blink Strikes; [talent: 5/3] Stampede
/cancelaura Hand of Protection
/petattack [@pettarget, noexists]
/cast [talent: 5/1] A Murder of Crows; [talent: 5/3] Stampede
/startattack
```

#Dynamic Level 90 Talents + HoP Cancellation + Combat Maintenance (GT Exempted)
```
#showtooltip
/cancelaura Hand of Protection
/cast [talent: 6/1] Glaive Toss; [talent: 6/2] Powershot; [talent: 6/3] Barrage
/petattack [@pettarget, noexists, talent: 6/2] [@pettarget, noexists, talent: 6/3]
/startattack [talent: 6/2] [talent: 6/3]
```

#Aspect of the Cheetah, Toggle Disabled
```
#showtooltip
/cast !Aspect of the Cheetah
```

#Draenic Agility Potion + Out-of-Combat Pet Movement Increase (Dash/Dive)
```
#showtooltip Draenic Agility Potion
/cast [nocombat] Dash
/cast [nocombat] Dive
/use Draenic Agility Potion
```

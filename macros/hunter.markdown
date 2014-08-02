###Dynamic Level 30 Talents
```
#showtooltip
/cast [talent: 2/1] Binding Shot; [talent: 2/2] Wyvern Sting; [talent: 2/3] Intimidation
```

#Dynamic Level 60 Talents + HoP Cancellation + Combat Maintenance
```
#showtooltip [talent: 4/1] Fervor; [talent: 4/2] Dire Beast; [talent: 4/3] Thrill of the Hunt
/cancelaura Hand of Protection
/petattack [@pettarget, noexists]
/cast [talent: 4/1] Fervor; [talent: 4/2] Dire Beast
/startattack
```

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

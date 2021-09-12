# FF14 - Macros and waymarks
Macros and waymarks for some of the extreme and savage fights. These may or may not be specific for some specific strategy, but I've used these myself.

## Extremes
### Hades
#### Macro
```
┏━━━ Spread ━━━┓┏━━ Stack groups ━━┓
┃　　　　　　　　┃┃　　  　　　　　  ┃
┃　　  　  　　┃┃     　   ┃
┃　　  　　  ┃┃     　   ┃
┃　　  　  　　┃┣━━━   Towers   ━━━┫
┃　　　　　　　　┃┃ ━ NorthEast　  ┃
┣━  Ascian Prime   ━┫┃ ━ SouthWest　┃
┃　　　　　　　　┃┣━  Ice knockback  ━━┫
┃　　　　　　　　┃┃　　　　　　　┃
┃    ┃┃　　　　　　　　┃
┃　　　　　　　　┃┃　　　　　　　┃
┃　　　　　　　　┃┗━━━━━━━━━━━┛
┗━━━━━━━━━━┛
TANK ADDS at NE/NW to grab tethers, healers grab S tethers
```
![Image of Hades macro ingame](HadesEx.png)

#### Waymarks
```json
{"Name":"Hades Ex","MapID":693,"A":{"X":100.0,"Y":0.0,"Z":81.0,"ID":0,"Active":true},"B":{"X":119.0,"Y":0.0,"Z":100.0,"ID":1,"Active":true},"C":{"X":100.0,"Y":0.0,"Z":119.0,"ID":2,"Active":true},"D":{"X":81.0,"Y":0.0,"Z":100.0,"ID":3,"Active":true},"One":{"X":95.0,"Y":0.0,"Z":100.0,"ID":4,"Active":true},"Two":{"X":105.0,"Y":0.0,"Z":100.0,"ID":5,"Active":true},"Three":{"X":0.0,"Y":0.0,"Z":0.0,"ID":6,"Active":false},"Four":{"X":0.0,"Y":0.0,"Z":0.0,"ID":7,"Active":false}}
```

## Savages
### E9S - Umbra
#### Macro
```
┏━━ Spread ━━┓┏━━ Flower ━━┓
　　　　　　　　　　　　
　　  　　　　　　　　　
　　   　　　　　　　 
　　  　　　　　　　　　
　　　　　　　　　　　　    
┗━━━━━━━━┛┗━━━━━━━━┛
 DPS clockwise        CHAINS / N/E - DPS S/W
┏━━ Platform ━┓┏━━ Tower ━━┓
　　　　　　　　　　　　　
　　　　　　　　　　　　
    　　　　  
　　　　　　　　　　　　
　　　　　　　　　　　　　
┗━━━━━━━━┛┗━━━━━━━━┛
```
![Image of E9S macro ingame](E09S.png)

### E10S - Litany
#### Macro
```
┏━ Shadow Cleave ━┓┏━ Voidgate Pairs ━┓
  　　　　　　　　　　　　　　　
  　　  　  　　　　　　　　　
  　　     　　　　       
  　　  　　　　　　　　　　  
　　　　　　　　　　　　　　　  
┗━━━━━━━━━━┛┗  Drop Bog Cardinal  ┛
┏  Voidgate 2 Part 1   ┓┏  Voidgate 2 Part 2   ┓
 　● 　  → ●　　　　　　 
 　↑　　　　　　　　　　　　　　　   ●
   　　　　　　　　● 　 ●
   　　　　　　　　　　　　　 ●
 　　　　　　　　　↓　　　　　　 
 　● ←  　 ●　　┗   Pairs move CW    ┛
┗    Clone in corner   ┛
```
![Image of E10S macro ingame](E10S.png)

#### Waymarks
```json
{"Name":"E10S Litany","MapID":748,"A":{"X":100.0,"Y":0.0,"Z":85.0,"ID":0,"Active":true},"B":{"X":115.0,"Y":0.0,"Z":100.0,"ID":1,"Active":true},"C":{"X":100.0,"Y":0.0,"Z":115.0,"ID":2,"Active":true},"D":{"X":85.0,"Y":0.0,"Z":100.0,"ID":3,"Active":true},"One":{"X":85.0,"Y":0.0,"Z":85.0,"ID":4,"Active":true},"Two":{"X":115.0,"Y":0.0,"Z":85.0,"ID":5,"Active":true},"Three":{"X":115.0,"Y":0.0,"Z":115.0,"ID":6,"Active":true},"Four":{"X":85.0,"Y":0.0,"Z":115.0,"ID":7,"Active":true}}
```

### E11S - Anamorphosis
#### Macro
```
┏━━  Protean  ━━┓┏━━ Shining Sky   ━━┓
　　　　 　　　　　   Lightning + Tanks: N
　　  　　　　      Fire:  Stack (S)
　  　    　　  ┗━━━━━━━━━━━┛
　　  　　　　  ┏━ Cycles of Faith ━━┓
　　　　 　　　　　  Fire: Protean → Pairs
　　　　　　　　　　　   Line → KB → Stack (S)
  Fire: DPS clockwise
  Lightning: / out     Lightning: Protean → Spread
  Holy:　　　　　　　　   Line → Out → Prey (N)
       North
       West　　　　　　  Holy: Protean → Cones
       East　　　　　　    Line → Bait → Prey (N)
┗━━━━━━━━━┛┗━━━━━━━━━━━┛
```
![Image of E11S macro ingame](E11S.png)

```json
{"Name":"E11S Anamorphosis","MapID":752,"A":{"X":100.0,"Y":0.0,"Z":90.0,"ID":0,"Active":true},"B":{"X":110.0,"Y":0.0,"Z":100.0,"ID":1,"Active":true},"C":{"X":100.0,"Y":0.0,"Z":110.0,"ID":2,"Active":true},"D":{"X":90.0,"Y":0.0,"Z":100.0,"ID":3,"Active":true},"One":{"X":93.0,"Y":0.0,"Z":93.0,"ID":4,"Active":true},"Two":{"X":107.0,"Y":0.0,"Z":93.0,"ID":5,"Active":true},"Three":{"X":107.0,"Y":0.0,"Z":107.0,"ID":6,"Active":true},"Four":{"X":93.0,"Y":0.0,"Z":107.0,"ID":7,"Active":true}}
```

### E12S - Eternity
#### Macro
```
┏━ Spread  ━┓┏━  Titan/Shiva Groups ━┓
　  　　 +  → N/W(Red/Purple)
　      　　 +  → S/E(Yellow/Blue)
　  　    Share Beam → S/E
┏━━━━━━　Shiva Slide 　━━━━━━┓
　 Left In　　　　　　　　　　 Right In
　 Left Out　　　　　　　　　 Right Out
┏━Titan ━┓┏━Titan ━┓┏━Titan ━┓
　H TH   　　   TH   　　　　TH  
　T  　　 　　     　  　　TH  　   D
　D D　 　　   D　 　　D　 　　
　D D　 　　   D　 　　D　 　　
┏━━ Big Lions - Cross Lion Uptime Strat ━━┓
　N:  →  → 　　 →  → 
　S:   →  → 　　 →  → 
```
![Image of E12S macro ingame](E12S.png)

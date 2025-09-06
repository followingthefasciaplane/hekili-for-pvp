## intro

hekili priorities focusing on arena/solo shuffle/battleground blitz gameplay

## fury warrior slayer
- patch: 11.2.0
- talents: `CgEArbixk/ZKwTdpZGVHeylmLAAAAAAAAAQjZMzwM2YMmZswMzMmhZMzstNmZmxygxMmZmZsMMzwMDAAAixy2AbgJYGmAzwGA`
- display: primary only 5 icons + single target + all toggles except potions

### aceserializer string for hekili import  
```  
Hekili:LA1xpQnoq8VnOT62lneoyzVUHhUhoPDFOQsS3dNo1qmodelsIJSDGLti)z)g7aeNazz7vv12G9m)(n)1Zenm61O5jefe91a)GX(p6pXB44XdhhenxTVeIMxsOBiRXpki54)(TTF7pRe7nNVpJtsm6l5vckEx08LvSm1Zfrl7a6yp)r(b(dJMtQuPCHr2uwsculkiPrZ)BeHmMujTMeSIuLPWp)Q1eHcYYmij6pIMtfmfiyedBRw5TKOuzWczkVs5LW3vGCqvmo()UxfPqJPxKueXAavhPNuqbD8SqD8q)gOOPgjmGm6gMtgbDhfxK7vvQJhOJVeBD80gKTYUyjpZAI)2h3eFcnXPwgUthB5wa0nzGuwG)1Y(HdhVHSLG6Bp7touNYPB2r2A9RX9Y8j4XCcuizBXiQ1eo5GPajtL6vsv1g1yFKLAYpP6sqibXgqCdvFWVLbYYlHIewX6fBzumoT3yOtE)eauiWY1ovc8czgPADQng)WhcGQYg1DdSgeM((i0kpymeRV2h415gdSp((W6KepNy7KYBqvLwvKacELCHGxdpwp)XC8F8IkZzhlq7Msh1oL20FynPB0C7KmRjX(tALqafQ6Uu7j5K3CmSJ5AehSYrQeSnG0dl8OBQvzStMLKxsQBSh2)ZdjGf3CcwcNSyfxSaEdOvgiCXDudU13xJ7nEXO2htwiG1qbiiwu7P)yIVBKKZtuPmH0wvp0(0XLf8omBKQ)286qxL5r5fjabP1X1cUURnXLZtXYom(GRmNuUJm3OHY6Qub5FHEsJDJfp22UwBkeqz21H3aFx5CbPLC4plX2aEooq58ePRoKPd8g5u81RZatgXrNoph2LoeOTOigzBnb1hD5Derb6oYO5VMYK64sbFfldNhy(rotkXl1XYQYsUaRAWIvDSTWIrXEuSLydOKE6yD8ZQALSUwo(qlKGsKsWJbK(9gSzCmtGFXkOzvyJlEftLcIFx)Io(x1X)ZFjbdsqU873RJ3LYOPUstk23WQoUGBa)TYmgLPYAWnX8LHCOH0VOJrB)inVwdbou(7gqtCpkWH5DSSmhp6iKQtIAJg2JkQYXSGHyzgx5PF55CtaZCqaYGnrPJT7JGxIZklbko6iWukyd4NYMsVZ1g)s4NDRg0VCvj6K7VVUajeP7LZA0bP7zRcV(YoUAuVJIr2o7kmlCOVRGnRC0aS7Ald6Q)0wAFARHRW0tHthC31gBC4q7rghoCX4INch7)jxIUy6VHW76BvKbDq6WH76B1JwI(qBsp)W55qJ7mihbDDWUYAE9()9FC4OoCDg9l2RyWpiPoq3z)GZC4KHU(4)3d0MQOlJi)e1fJANIooN5AjOdhCxqyw4PLdost)lgmlCSlfhhtzO4MZ(Nfo6JeWDMU0XYVy0FR6Zj(xT8ShRTNH4ZcdU0IoghVcs3YU7op2e96leCZaJZ45E41orm6)o
```  

### apl import  
```
actions.precombat+=/battle_shout
actions.precombat+=/berserker_stance,toggle=on

actions+=/battle_shout,if=buff.battle_shout.down
actions+=/charge,if=target.distance>=10
actions+=/storm_bolt,if=buff.bladestorm.up&target.distance>8
actions+=/shockwave,if=target.distance<=8&(buff.recklessness.up|buff.avatar.up|target.health.pct<=50)
actions+=/impending_victory,if=(buff.defensive_stance.up&health.pct<=50)|(buff.berserker_stance.up&health.pct<=70)
actions+=/onslaught,if=buff.enrage.down
actions+=/recklessness,if=buff.enrage.up                             
actions+=/avatar,if=buff.recklessness.down&buff.enrage.up                
actions+=/thunderous_roar,if=buff.avatar.up|buff.recklessness.up         
actions+=/bladestorm,if=buff.enrage.up&(buff.recklessness.up|buff.avatar.up|target.health.pct<=30)
actions+=/rampage,if=buff.enrage.down|rage.current>=rage.max|buff.slaughtering_strikes.stack>=5
actions+=/execute,if=debuff.marked_for_execution.stack>=3            
actions+=/bloodthirst,if=buff.enraged_regeneration.up&health.pct<=60
actions+=/onslaught
actions+=/execute,if=buff.sudden_death.stack>=2   
actions+=/rampage
actions+=/execute
actions+=/bloodthirst,if=buff.bloodcraze.stack>=5                       
actions+=/raging_blow
actions+=/bloodthirst
```

### video
[![video](https://img.youtube.com/vi/zxu4SgpSPtM/maxresdefault.jpg)](https://youtu.be/zxu4SgpSPtM)


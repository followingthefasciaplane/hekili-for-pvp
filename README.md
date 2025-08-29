## intro

hekili priorities focusing on arena/solo shuffle/battleground blitz gameplay

## fury warrior slayer:
- patch: 11.2.0
- talents: `CgEArbixk/ZKwTdpZGVHeylmLAAAAAAAAAQjZMzwM2YMmZswMzMmhZMzstNGzMWGMmZmZmZsMMzwMDAAAixy2AbgJYGmAzwGA`
```
Hekili:vw5ZVTTnuC8)w6LEAtWwUoXDRRh2T0dbbqzdOOOuKM8zjctrkqszxxuW)23Jujr0ErjThSbf5tF(((jfzj5EsLG5bYTLlkxVyZQfflw9UY1Biv(t9aPQNX3ZAWfAwh()DhUlU3jLHjIVRZmy54(KQTdsL)gnz7ZaCXMYLOT9aNC71LKQwPqaJMcooP6ZibL05Dj3b2XguEC5Tj3d0STkqq(Bsf3k9GvYivVjq3oSBxXwM3RGAxRzWxm0tQyCV0Or3j7aIh9Mzr5z2gWxiq9zAoeOF8Vc0ntK4TrdImwnlJrFrXWWXBSDONeO)4hb6dSBbMY3w0Z9b6hq6RwhOV9Ptpx5RMuoXQERrLIG39YQBb(Ef4CA83RP)6fzI0A47pYoKIW1ZQXlHq21dAHu3uFqYrF(ue1vVS7cAl2wvimh1tGmANIn00MI3R)PaKxZZtbrcB(fYyrhjvuMdo7adZMrSV)LXoA4tLGNR4mr13oOfG1m4QTMr8lx8tg4ZZp7Kl8M5AiZQMtTXjVz(zWlRJJkeFCStEzzgvlRRNnogTC(zrbKG2XS7br9oJTg(gWhIikWHe((rYRYcq3q8UKAbWWakZMYjThzmQ9RmdpgoIAl0aAWYskF29kkJr4BLwxQjDzAQ8)3)Mjr0Q15w9yQ4cBUk3MhD5lS5vMjsoh3Y(oCw2AEVFZ5(vtCggT54L6((C7YHCMD4J9yNOPdV89PRVF2lKphFQFWBAAuqmhM9oG1byRGTE8gYlLdbDKz1Ox7iv33kDbAV1StQWoW4dDsNdpmqDd99gl2SJTubAQ0k540GvQ3dExrGgO34hFPue0HxObc0IwgUnCaSNISLgmHJRKAUAaNsWJK(wW(hHpfO)EG(L)XbrsqN7R)wGESvYBZTMPpnPAGQnr4FRxj5sVAIRiUkkomj6FgOOV)Gm3pIaNX(AeQiFRYmLpkvQSi6bK(hnnLnsBPh6WKDuyNY4lcF6MUyclUrjQqQEeOPVrJhgRZP0C8d)SbFRXsQ(xmhXng1X01yEc5)c
```


```
actions.precombat+=/battle_shout
actions.precombat+=/berserker_stance,toggle=on

actions+=/battle_shout,if=!buff.battle_shout.up  
actions+=/charge,if=target.distance>=8 
actions+=/storm_bolt,if=buff.bladestorm.up|target.health.pct<=35&target.distance>=6
actions+=/shockwave,if=buff.recklessness.up|target.health.pct<=50
actions+=/impending_victory,if=health.pct<=50    
actions+=/onslaught,if=buff.enrage.down
actions+=/recklessness,if=buff.enrage.up                                  
actions+=/avatar,if=buff.recklessness.down&buff.enrage.up                  
actions+=/thunderous_roar,if=buff.avatar.up|buff.recklessness.up           
actions+=/bladestorm,if=buff.enrage.up|buff.recklessness.up|buff.avatar.up|target.health.pct<=30
actions+=/rampage,if=buff.enrage.down|rage>=120
actions+=/execute,if=debuff.marked_for_execution.stack>=3|buff.sudden_death.stack>=2                            
actions+=/bloodthirst,if=buff.enraged_regeneration.up
actions+=/onslaught
actions+=/rampage
actions+=/execute
actions+=/bloodthirst,if=buff.bloodcraze.stack>=3                           
actions+=/raging_blow
actions+=/bloodthirst
```



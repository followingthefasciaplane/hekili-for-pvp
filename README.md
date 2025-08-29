## intro

hekili priorities focusing on arena/solo shuffle/battleground blitz gameplay

## fury warrior slayer:
- patch: 11.2.0
- talents: `CgEArbixk/ZKwTdpZGVHeylmLAAAAAAAAAQjZMzwM2YMmZswMzMmhZMzstNGzMWGMmZmZmZsMMzwMDAAAixy2AbgJYGmAzwGA`

```
actions.precombat+=/battle_shout
actions.precombat+=/berserker_stance,toggle=on

actions+=/battle_shout,if=!buff.battle_shout.up  
actions+=/charge,if=target.distance>=8 
actions+=/storm_bolt,if=buff.bladestorm.up|target.health.pct<=35&target.distance>=6
actions+=/shockwave,if=buff.recklessness.up|target.health.pct<=50 
actions+=/onslaught,if=buff.enrage.down
actions+=/recklessness,if=buff.enrage.up                                  
actions+=/avatar,if=buff.recklessness.down&buff.enrage.up                  
actions+=/thunderous_roar,if=buff.avatar.up|buff.recklessness.up           
actions+=/bladestorm,if=buff.enrage.up|buff.recklessness.up|buff.avatar.up|target.health.pct<=30
actions+=/rampage,if=buff.enrage.down|rage>=120
actions+=/execute,if=debuff.marked_for_execution.stack>=3|buff.sudden_death.stack>=2  
actions+=/impending_victory,if=health.pct<=50                              
actions+=/bloodthirst,if=buff.enraged_regeneration.up
actions+=/onslaught
actions+=/rampage
actions+=/execute
actions+=/bloodthirst,if=buff.bloodcraze.stack>=3                           
actions+=/raging_blow
actions+=/bloodthirst
```



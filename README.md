## intro

hekili priorities focusing on arena/solo shuffle/battleground blitz gameplay

## fury warrior slayer:
- patch: 11.2.0
- talents: `CgEArbixk/ZKwTdpZGVHeylmLAAAAAAAAAQjZMzwM2YMmZswMzMmhZMzstNmZmxygxMmZmZsMMzwMDAAAixy2AbgJYGmAzwGA`
- display: primary only 5 icons + single target
```
Hekili:nwztpUjmqy4Fl9sv7feKSjBQuBp0B9s0krV0lgCSh(qXyJSnjnvR43EhBAwmSHDZHeXhZ8mVE87yijKFrs5ulq2VkE1M4DRJJIFij(HTKu7LwGK2szhPL4fsAd()tNEY9SlcfL7Y1O60m85K0dD1c7pLKdVg464DRsWyBbgz)JRiPv1ComekyyK0FJee1gRXlhOG2jS4L79YdK0dcGt(bjLPRTGUMss)qF(HUIIOduRvazMkvNnQRLKsz2ALeLtWliwunlIYs1LGnIJ1NkzqF(3)wF(UrsSkxaogRDm6mqMQOiRKXDc8LWmwLUj7Gcv(BcVpFBF(hVkFbf7aUmrX3N)8Z95)pJkGkSvrTmBF(xrbTEtO8rX8W9VGC5huunWokaJrI)EVYUjoyfwPyhptp57fBwS8VgXqf(011mOnG(iOZg0NxcO2MN3JyEFES61nTGKxllZovZWo2fNk2UOk8LcKA07gXvNLJGusJG2vw5TfpExacnwHDphHDVnHjnBNqg3hUbC6jkUr4W(L3g7qGVS7DR91rQ2Qojh0QotMwnGpj(ox4VJT5wIzjhCGvA037fZYZ5Z3ghQG72H50Kvbu10Mw6WOAYYZ7CWdTHIEqEwHsNb)byDoerOJKDCG86rUdVFG767rQ8mnucsqt9uNCUKqP42QATX7)s8JXV2AoDwpztyuxxMZIzBymxL8SyEh7UxCmn9VWcDI5QF3uDv6gpXyopVUFjmUqitIdVTfDzQg8W7xo()MhOpfVFV2QklfGRhgKZSJAMxoe0zQwIQ24(ewRwvul8FnJ2zRuA8kxqK)9d
```


```
actions.precombat+=/battle_shout
actions.precombat+=/berserker_stance,toggle=on

actions+=/battle_shout,if=!buff.battle_shout.up  
actions+=/charge,if=target.distance>=8 
actions+=/storm_bolt,if=target.distance>6&buff.bladestorm.up|target.health.pct<=35
actions+=/shockwave,if=target.distance<=6&buff.recklessness.up|target.health.pct<=50
actions+=/impending_victory,if=health.pct<=50|(buff.berserker_stance.up&health.pct<=70)  
actions+=/onslaught,if=buff.enrage.down
actions+=/recklessness,if=buff.enrage.up                                  
actions+=/avatar,if=buff.recklessness.down&buff.enrage.up                  
actions+=/thunderous_roar,if=buff.avatar.up|buff.recklessness.up           
actions+=/bladestorm,if=buff.enrage.up&buff.recklessness.up|buff.avatar.up|target.health.pct<=30
actions+=/rampage,if=buff.enrage.down|rage>=120
actions+=/execute,if=debuff.marked_for_execution.stack>=3                          
actions+=/bloodthirst,if=buff.enraged_regeneration.up
actions+=/onslaught
actions+=/rampage
actions+=/execute
actions+=/bloodthirst,if=buff.bloodcraze.stack>=3                           
actions+=/raging_blow
actions+=/bloodthirst
```

**video**

https://youtu.be/zxu4SgpSPtM?si=S6JX7n-Mc5x9o6v7
[![video](https://i.sstatic.net/zxu4SgpSPtM.png)](https://youtu.be/zxu4SgpSPtM)


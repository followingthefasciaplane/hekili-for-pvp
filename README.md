## intro

hekili priorities focusing on arena/solo shuffle/battleground blitz gameplay

## fury warrior slayer
- patch: 11.2.0
- talents: `CgEArbixk/ZKwTdpZGVHeylmLAAAAAAAAAQjZMzwM2YMmZswMzMmhZMzstNmZmxygxMmZmZsMMzwMDAAAixy2AbgJYGmAzwGA`
- display: primary only 5 icons + single target + all toggles except potions

### aceserializer string for hekili import  
```  
Hekili:TEvuVjooq4)nv7QRhBawkT3v6d7BTpuTs07HtN2qmjdelCSJSDG2ti)B)gBhiMqsP3D7wTiJZmFFJNz88fIhg)s88mIgIFEu0Ojr3fnzq04VoA804563kH45LK0nK14coPa)87B)(i8F29FJjizw)vIkzk(S45lROm9J84LDaA0OOHXZjv6CH0ABonld8McQ045)PLmPyfLHliPAQGRgukHurXsI(xM9f8tndwOYfvAZtDAbivGCdixO0eEkCTwSEndMj4MNo6rlKUMUA2YQvRgeU5GmXoEOhP5e5AWAR2UanG6P4Hz3AscTuPfYIflfSaKze8iA3Fqv5j2Mls3SJSTlGVF2WOR(KZF8eUHbkfh)pIW(9UDjBjOlUVx7Aoqy68bLP67Nnj6ZHmrlkbEgLVEXwAkgjVzz0JEgSc4k6wOoPHiEvlK2V3BA78BBtNEkP4Nms168MmbWLyV0zz3WdyBBXmwY)5)c4WNUoI(j5uB8C1)ssdGwNxXZaPOsTqkc4iOc1vD89bTPP58mY)J(IXNwIKKIsIVXUDbA)E3Y0kPe46hM5(wb51AAQlTG02uP0s6gqnaBls38WSjHuaVcPvAhfzGZ1cc2dLTyLqUW)q0YdUo(JKWxYeImDovQA3ALTqcRboijoqB1FEtuNTN9eT(JzLDk1ImGGGuhJJopIQZJDG0LIB3EPsYFdnzV(sbxmXGPaB5aXCxp8gpFlEjg3)0zZrtINVJi5O3Q45VKtvMK6HXMe7xkOkf(qtIQQSui1MeS8zsC5AAQjbBa4BaTAGnKEu7DYnAUah8azOf5eCBaP)nl2uHKQXvuEkRc70Xhr15G83Wr1j)Qj5V(dfyrcku)4AtYUCAAEO1e(BnSAs4cl4VwYOPunRb3m7kl5qdP)UjbJ9AAEXdHjz4pSGMfU1OaM3rzSGtunK6dM6YgUT4vf4CslXkMqpW80Jf2eMDdSXXxumjmCmpMSEcvplH04NNIsQU9CcYWksftJlF2jqdCYsgKf)T45P4baZ4eRwBxIwhKoXNh8OynwU7fPwkpMKhMzsUTbjV4NfJXxiAcf6A8Vrs0IXx)4XX9yCmmYKCLj5tMKUNHUFF9too3ZV3zZ(8WnbH7ZbH2bfyBKnP3i7a7DOv6IUozXhhhCTdTZoDD6Pb4zc32a9M3VmemeVbOJt7Sam9dbqynmmVBr423hHZKxDN1(a3x6SWE37dBRACxDenO2sw2c)WOp4b)NAp34tlPn3sCH0fUHh(ktoscvL9xvpOmhey9Ro7DzsqL1lD5IL(NrCrPBpUJBWTw)ZH7fMB0J2DN3pUjkmt2ORzPXnA58g(aMTw1)18Eu89hTrDF0UjKZd5Ywmon0Mdo3YMlCHQ9RjCwzSDU4UtJRJVxqlEhffA3jVOqODA7VnR(hADuwQtLMwWBTZ)RWSvKaFAnoSnD()I)Nd
```  

### apl import  
```
actions.precombat+=/battle_shout
actions.precombat+=/berserker_stance,toggle=on

actions+=/battle_shout,if=buff.battle_shout.down
actions+=/charge,if=target.distance>=8 
actions+=/storm_bolt,if=buff.bladestorm.up
actions+=/shockwave,if=target.distance<=10&(buff.recklessness.up|buff.avatar.up|target.health.pct<=50)
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


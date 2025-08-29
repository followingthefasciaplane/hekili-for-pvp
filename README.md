## intro

hekili priorities focusing on arena/solo shuffle/battleground blitz gameplay

## fury warrior slayer:
- patch: 11.2.0
- talents: `CgEArbixk/ZKwTdpZGVHeylmLAAAAAAAAAQjZMzwM2YMmZswMzMmhZMzstNmZmxygxMmZmZsMMzwMDAAAixy2AbgJYGmAzwGA`
- display: primary only 5 icons + single target
```
Hekili:nwvtpUjmq0Fl9sv7Lii0KnRuBp0B9YQvIEPxmmXE4dfInY2K0TAf)27ytZIHnSBoKid8M37nJNXMfZ(flvawK9W6O1BI2LeTk6lrjXBzP2NArwAlWpaL0cjCK()Xtp6E3tnkq4I1O60C69S09D1n2Fkz7FnHjr7whtyBro7H7wZsRQfcCakA4S0Ftm0uBSgVDWcORXslFWBpuc7Bqb7hSuUU2I6AGL(H(89DffR2dwBdMzQuD2vDTSuGBRvsYobFGzj3SivwqxI2vcsFqYX(8V)T(8DJmXRCaCCK44OZGzQIISsUWzWxGzSk9XS9kY5Vj595B7Z)4f73aufWfjz((8NFUp))ruHqJTAvl32N)vYqjBcTpzMVC7jKl(ar1i)qdAms637j7MOGmSsXpCgo5RfBwu(xtXGcF6soJAdQpG6Sb)5Ta5T5XDhf3NhvV(ylkf1YYSt1CQI9KZfBx0fEPqPM6DxjuNLJePKMgORSY3wC3nrqyJvy1ZXWU3MHjfBNrg3hUc5WjG2iC0E)Bt7aWx29U2(6iR2QoPa1QotMwnqFC0nM4VtBZ1mZsDWbTsJ99EZS8C(8TXbfCpomNgVoGvnCSfggvJxEExGEspcupOiRqPZW)G8ohfROos(HbMtcsqtN78QmbcucfGz9O2dCmODYTKoImnwIsudELNC2vJsjSv1AJVhn2pQ)623PNheVje1LsXmmBdXCXYZW8oJeEZX1WFXjvRLD)UP(Q0nctyopx37dXfsYeC0JTuNO6iDa)lxrC1d9NsVVFWQklBqxnmiMzhhnxoIOZGwsU24UMRvRkQB834bD2kLMw5aX(3p
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
actions+=/execute,if=debuff.marked_for_execution.stack>=3|buff.sudden_death.stack>=2                            
actions+=/bloodthirst,if=buff.enraged_regeneration.up
actions+=/onslaught
actions+=/rampage
actions+=/execute
actions+=/bloodthirst,if=buff.bloodcraze.stack>=3                           
actions+=/raging_blow
actions+=/bloodthirst
```



## intro

hekili priorities focusing on arena/solo shuffle/battleground blitz gameplay

## fury warrior slayer:
- patch: 11.2.0
- talents: `CgEArbixk/ZKwTdpZGVHeylmLAAAAAAAAAQjZMzwM2YMmZswMzMmhZMzstNGzMWGMmZmZmZsMMzwMDAAAixy2AbgJYGmAzwGA`
```
Hekili:vwzWUTnoqy4NLEPN6kylVoXTD7EyVLEiOakTaffLI0KJLimfPajLDCraF27qQKiA34KShsGe5OV))z4m0K5KBivcMhixxoRC5SvlMvmBXIYYvKk)HEGu1Z4Bzn4dAwh()VS7lX1oOmmr8BDMblhxNuTEqQ8xPjRFcGZwvohJTh4KRVSKu1kfcymuWXjvFhjOKoVlzhydBq5XhVozpqZwRab5)ivCR0dwjJu9MaD9WMnfRzEVcQDTMbFXqpPIX9sJgTt2gep6MZIYZSnGVqG6Z0Ciq)3pfORMiXBJbezS4Smg9IIHPJ3y7qNeO3DxGEp7wGP8Tf9CFG(pi9fld03(4UhR8ftkNyvV2OszWF)8QBb(wf4CA8Vxs)LZYeP1W3UNTlLHlFEnaTf7fkeM96jagTtXgAAtM8IxfG8dQCFhjC5)J0mAKuL8CWz7yyjiID1ZJDmWhRBpvfDIQVDqlaRzWvBnJ4F)RmVpp(SDoXmNRjk7qCQ1lAM5ZEvUzS6fvi(6y338YmQwwxpBS1F(5hffqcAhZUfe1Bm2A4wGperuGn28TJKxKLGUH48FTayycLft5K2Jmg1(8ZUpxJTSRh0cPUPENKJLMdjwVWm8yPruBHgqdwwklo6EfLXi8TsRl1Vppnv(NJczseJAzEupuwpjMlYJ5H0)KyEHHJK54w2VGJQ8N39Ro2xnXQfgZ(t1995XLd5O4Wx7XUAthE57JxF)KxiFm(05R300OGynm7BaRdW2kB94nKNkhcApZQrx7iv30kDbAV1SrQWU54lDsNd3mqDd99gl2KGTNbA6OvYXjlRuVf8UIanqVYp(rPmOdBDabgrldxg2b2dr2sdwWXNKAUAaN4WTK(wW(HWNd0)kq)XxDqKe05(57c09TsEBE0m9HjvduTjc)2ELKl9QjUI4trXHjr)yGIE)EzUzeboV(Ziur(sLzkVxQuzz09i9peAQAKwsp0Hf7OWoLXxe(8vDXcwCHsuH05rGM(nACZ45CQmh)HF2GV1yjvFdRrCJrTpDJONq(9p
```


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



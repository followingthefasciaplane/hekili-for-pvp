## intro

hekili priorities focusing on arena/solo shuffle/battleground blitz gameplay

## fury warrior slayer:
- patch: 11.2.0
- talents: `CgEArbixk/ZKwTdpZGVHeylmLAAAAAAAAAQjZMzwM2YMmZswMzMmhZMzstNGzMWGMmZmZmZsMMzwMDAAAixy2AbgJYGmAzwGA`
```
Hekili:LAvxVTTnu0Fl9L8YY08hZPoB1(H9wYdbfqzdyyOuKMI2IWuIcKu21fg83EVKYwIswoUlfgjGM8WZ5(fVxJgJEffNsmm0ltgnz2O5thfnA6OhhpdfBouYqXLe6wYgyrbjh()N39z3EhessQ7UAzLIc7JIxvXfMNkqRgIW5tgdylzu0lFCckoJNMYQHY0uu8)cmi4AJ2BoS1KkHbw(I38yfKvcwk6VqXuf3WuCck(dw8QQ1RJwrmgblrNjRmrvLOyc1WLfG5eCaYawZvPYquByMOuqFsbLzXlxyXZBzIM5a44y6v5O2weeWDmsvoyjw8XJw8jUZyeHjlQKAS4pbSpDMfF35tt6Q8dTk75kzLu49GF)TvxXOBfmTUa(7w6pBuGizs629KDEpC2BRbRqb1crPY9fTeil0cs1MmVr(W7GafjVKuhH)4p01dZZHUTJH5)pIsoZWNiUg5KDeic6O9X3M2AGnH9HsiTSAYQkszkzLorjRPF8OFqh)68hCspR5AfHbfbTLUER56V7szEfYjQTS0K1svc7RmALJLiOkMUTUiEAG1ORCp2tszeq9amtALVMdFfW4R)q9TQI55LSIuEXMKDCk4hh8CDJhS1r10efBdRGPiEVOtteHuMAY4kTV4ES)j4L19bs4qnle15I7EyEieZz3VhMB8yWBCuf5BSor(RB9Z7AxBCrlaZ((6(yiUqs6Gd(AjuckZHoTn9QhS7Bx695xJCZgbZfddUdtPzqzLkPUDyF5aI2tufGvRrXVMX1wCPsUMlGgNUVKZ1A4qlwxvwkvqrcuEAX(ulNcpdu8ITmJoYIT4Nm1xY7b5qPdlfqKrGTz7yQdoU5siGdR4furf88aoIBYyQ)W(Sf)Rw8)93AMJjwU(l3BX7Z40Sq0KIdTQAXfsh5FTuWPCJOL3u3kN4Swr)tlgS9tY8Anfw84V4innCRjbkVNlebE0jknNH6Jg(TkQYHGTtyTqAISp)uUlG52ycOGpFyX(bYWHU8SpmFovPJAs8)YIFlmvBFEqe9sS3xN9xaI8CZn6X0981l(Wqt4DjVWlvpD2bV3C8LlM3fz70uh6lNyF84fnk)0IPZUR3u6LlEOdRNhF2qAV(Yds7SrDTTMEjnSemPme4P2j3ewGn0h7Py4p7Na1QN3mCaWzz39oKpG(EZlB0Pzm3XJdpq8we3M(VmgnmNN2nq5HQzg1xOtn4DQCZbOlxm9Kkxo4C5Ij9P(IbForUOu79)Pt4QzuqV41fJqhS2EG64bcs3sX(J9G41nDIB6AbtdVI(qZVktMuHI)hy8avkf79)0ndc99p
```
```
actions.precombat+=/battle_shout
actions.precombat+=/berserker_stance,toggle=on

actions+=/battle_shout,if=!buff.battle_shout.up  
actions+=/charge,if=target.distance>=8 
actions+=/storm_bolt,if=buff.bladestorm.up|target.health.pct<=35&target_distance>=6
actions+=/shockwave,if=buff.recklessness.up|target.health.pct<=50 
actions+=/onslaught,if=buff.enrage.down
actions+=/rampage,if=buff.enrage.down
actions+=/recklessness,if=buff.enrage.up                                  
actions+=/avatar,if=buff.recklessness.down&buff.enrage.up                  
actions+=/thunderous_roar,if=buff.avatar.up|buff.recklessness.up           
actions+=/bladestorm,if=buff.enrage.up|buff.recklessness.up|buff.avatar.up|target.health.pct<=30  
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



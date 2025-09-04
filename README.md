## intro

hekili priorities focusing on arena/solo shuffle/battleground blitz gameplay

## fury warrior slayer
- patch: 11.2.0
- talents: `CgEArbixk/ZKwTdpZGVHeylmLAAAAAAAAAQjZMzwM2YMmZswMzMmhZMzstNmZmxygxMmZmZsMMzwMDAAAixy2AbgJYGmAzwGA`
- display: primary only 5 icons + single target + all toggles except potions

### aceserializer string for hekili import  
```  
Hekili:TE1sVnUnq4)nbzr3QklxNhTX5qVLCiybC6HIIvw0sJTiSePajLDsHb)T3HKYwuYsXPpIrmOPM57BEXzOINe)A8ImIcIFjkmAw49HZccNojA6DXluVxbXlQiPBjBWfmsj(9329Ti8pZ(VxWjzg9L8Ark(S4fRQPfQNyXRga0WOWjXli1QCUWiBonldCIcY04f)HHmbFnTaxqsvuotgujGuE5kI6hM)t43QcyPmNxR0ppOeGqcITGyPuryPWxv8nBkG5CM(5tA0dPVsxpFv961b(BgKX3Z81inNi2agzvMfOauhfpo)oDIVKsfxuUCfVWd5cc6IM9dQRoC46Eq8W8jHxLY5fgsdq(t3UNSdceqjHYKpoF2vnAKdKcvEqvQ6H5rZ(shApQ2a2OLGRTMcgS2wasjd)3Am2Dj7iOk2FpatZc7WeTScyzu2ML7OPOt9UHrh6zWAGjP7GM4pI4v9qcDFxmPxQQVO32Lu87cs9M82GkWeyz5zjkFhSVS1vyQ6F7hpoCHRtO3jMASNR(hsQh0Q8Awgi41YLcUhhEzOHYJFmOT1FNhr(puxmTBksqkRiUZi9tqhoyxMwleat94C7VkjV1qttQfeMIkPsq3cYaSSiDlw77tb8gKwRSuKbwvljynu2Y1CXs3drjpQ60ptaFvbNNPYPcz)sRSLcydWabXcAV6ZBchS8CeR15M1MgElZaccsJngDUf1ehhaPlz329sfK)cAJEJfcUyGbdbM0bI5(r4nEXo8qmUF328HZIxSNiyO2Y4fVMtL6KM(66eZpkPsj(qDISUQIlu6em9PtSXAAQoblayBbLmWyspPCkz7YxInEGmuICcUnG0)UbBkxqv4kklTOgR0Xhrv5G4xWU(j)Oo5p)DjyqckLF)R6K9500CFPjS3BzvNW4gWFRQGMsvfT4MzwzihAj9x1jOT3qZRoi0jt(Ub0m)TI8yEpTOWZJAGuDuuB0WUfRUe7tAiwwWvb6NFQ0eWmBGfoUKIoPaBZJbRNXbXvqA8l3ItNT7zNTdRj1fkC5l2z9aJSQaYI)T4fPOdGrCIzS9qZ)oofgFU3JIvy6EuK6n5rN84CDYDTi5MJAWy6fSg)zM6Kdh0jxJrL(W)ac)KqDYv6KXNG6SIzwPoRpMdJi8PFP1mBhIBm1F(Z7UE2dAUd3Q24lDBV62BetBwyxt7O3zSSzJAzhzFGrYwRBqwofNhBe9GQEBxd8S7hym0B(4ST3SIwGo1u1aWTFkaQRAv3pUBq4UpgHZMIB91Xa3L6mWE)hdBVC8qveTO2B6Vb(jHFsh))1AUPDtPThgTM0fAK4FZmlj(d)DNfpEbapdB8lb0C81lZ6MqATLXBfDXBi4WDAlUnJzT4EH2tJCfHbpFCtOFKSD8PHgBRLZl49y2i14hZh5IfoxlAyx7gFopgl7X4T(YCu5EYCHdu9VnYzPX(XI77AxNU(rpEJc9LRZ9r8LtzEBYMxn800VbhO1dEJCU3B0Kr80Px7W(05(e)3)
```  

### apl import  
```
actions.precombat+=/battle_shout
actions.precombat+=/berserker_stance,toggle=on

actions+=/battle_shout,if=buff.battle_shout.down
actions+=/charge,if=target.distance>=8 
actions+=/storm_bolt,if=buff.bladestorm.up|(target.distance<=10&cooldown.shockwave.remains>=5&target.health.pct<=25)
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


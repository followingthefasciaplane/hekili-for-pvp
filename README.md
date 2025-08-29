## intro

hekili priorities focusing on arena/solo shuffle/battleground blitz gameplay

## fury warrior slayer:
- patch: 11.2.0
- talents: `CgEArbixk/ZKwTdpZGVHeylmLAAAAAAAAAQjZMzwM2YMmZswMzMmhZMzstNGzMWGMmZmZmZsMMzwMDAAAixy2AbgJYGmAzwGA`
```
Hekili:LAvtVnUnq0Fl7LCPPQ(J1z92Uoh6TKdblGslqrXslAQXweMsuGKYEDHb)T3Hu2suYYXBtHrcOjF89MV4mMmM8kjoLAaYltgnz2O5thfnA64poDoj2COeiXLu2w6gCrbnh))x39v3EhesAQ7UAzLIH7tIxvXfMNkiRgGWrZNmgXwcmYlFAcjoJNMc1qbnJe)xidcU2O9MdSMwjm4Yx8MhuqxjGuYVtIzkUbuCkj(d2KvvRxhTIAmcyPotwzIQkjXuMHllqZj4aIbTMRsLHQ2aMOuuFAbdSjpUWMmVLjwMdGJJPxLJABrqr3Xiv5OLytoE0MCI7mGkmzrLmJn5li7tNztUR50Uk)qRYEUwUsk8EWhFB1vaBRa06c8VBP)SrbIKjzB3t359WzVTgqHcRfIsL7lAjqwOf0QnzEJ8H3bbkAEjToc)PFORhMNdDBhdZ)peLCMHprCnYP7Oye0r7NFBARb2e2hkH0YQjRQifuYk9sLSM(XJ(bD8RZFWj9SMRvegue0w66TMR)Ulf8kKtvBH0LRLQLW3bwLJLiSkMTTUiEAG1ORCp2xMcuu9amtALVMdFfW4R)q9TQI55LqrkVyZYDCg6hh8CDJhS1r10LkyduakQ3l60eriLPMmUs7lUh7FcEzDFGeouZcrDU4UhMhcXC297H5gpg8ghtr)hOtK)6w)8U21gx0cXSVVUFoexijDWHFTelbL5yN2ME1d29Tl9(8RrUzJaCXWG7aknGLvQL1Td7lhs0EQQaTAnj(1mU2MuQKR5cSXP7l5CTgp0MORklLkSiblpTj(ulNHpdu8ITGrhztSjpzQVK3dYXshifrKrXTHDG6GJBUed44kEbtuHppWJ4Mmq9R2NTj)Sn5V)dn4ycY1F7EBY(mollenT4qRQ2KcPJ8Vxk4mUr0YBQBLtCOv0FZMG2(jzETMcBY4V5innCRjbkVNlebE0jknNH6Jg(TkQYXGTtyTqAISp)uUlG52ycQGpFyt8dKXdD5zFy(CQsh1K4)Pf)syQ2(8Gi6LyVVo7Vaf55MB0JP75Rx8HHMW7sEHxQE6SdEVPPpUyExKTttDOVCI9XJx0O8llMo7U6Dx2Y7dDy984Zgs71xEqANnQRT10lPHLGjLHap1o5MWcSH(ypfd))(jqT65ndhaCw2DVd5dOV38YgDAgZD84WdeVfXTP)lJrdZ5PDduEOAMr9f6udENk3Ca6JlMEsLlhC(4Ij9P(IbForUOu79)Pt4QzuqV41fJqhS2EG64bcs3sX(J9W41nDIB6AbtdVI(yZVktMurI)tC8atkf79)0ndH8Vp
```
```
actions.precombat+=/battle_shout
actions.precombat+=/berserker_stance,toggle=on

actions+=/battle_shout,if=!buff.battle_shout.up  
actions+=/charge,if=target.distance>=8 
actions+=/storm_bolt,if=buff.bladestorm.up|target.health.pct<=35&target.distance>=6
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



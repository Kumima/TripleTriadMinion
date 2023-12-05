# TripleTriadMinion
## Please Trial Before Buying
* Dont start trial until you finish following
* [Discord](https://discord.com/invite/g8nnzfED2H)
## Install
* Only Windows7-x64 and above are supported
* Need MadaoCore,MadaoCombat,KumimaCore
* Download [Release](https://github.com/Kumima/TripleTriadMinion/releases)
* Unzip and put all files into C:\MINIONAPP\Bots\FFXIVMinion64\LuaMods\KumimaCore\TripleTriadTask
* The result should be: C:\MINIONAPP\Bots\FFXIVMinion64\LuaMods\KumimaCore\TripleTriadTask\win-x64\...
## Description 
### Cant Do:  
* Cant be fully auto, like auto finish a npc then move to the next(mainly because mesh problem and too many npcs need to be unlocked by quest). I'll try to make an auto mode after finishing my own navigation system(using madao's now, special thanks to him)
* Due to the above, you can only loop with one single npc(really sorry about this)  
* Cant assign cards into deck, which means you should manually assign suitable deck(minion cant assign cards into deck)  
* Cant handle multi run on one PC, mainly to avoid stuck(will try to make something after auto mode)
* Only support npc battle
### Can Do:  
* Fully auto battle with a single Npc 
* Support adaptive deck, which means any arrange of deck cards is supported(the performance depends on whether the deck is suitable for this npc)
* Support any kind of rule, support roulette which means it support others  
* Auto place best movement
### How It Places the Best:
* It considers your remaining cards and npc's remaining cards. It will also consider npc's potential cards
* It optimized all the rules, even "Three Open" is considered(i believe most human treat it as useless, but this will help make npc's potential cards clear)
* No matter how complex the rules are, it still works, even if there is a npc with four roulette in the future
### Notice:
* For some npcs, you should manually move to him nearby
* For the special rule: "Sudden Death", the bot may place the card very slow. It's to avoid death loop, in case all the game result comes to draw. You can simply ignore it, the bot will keep running and it will happen really rarely.

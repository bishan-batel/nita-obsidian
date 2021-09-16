# Player
## TODO
- [ ] Player.Create finite state tree (FST) (@2021-09-17)
	- [ ] Player.FST create individual states
	- [ ] 
## Finite State Tree States
- ### Dialogue / Cutscene State
	Used for taking control away from player during a cutscene or dialogue so they can't move while talking or being talked to (also provides functionality to force inputs onto Nita to make them move wherever)
- ### Sleeping State
	-Used for cutscenes but mainly used as a transition between the player movement state after they die. Before respawning, their state will go to sleeping first to play an animation. I could've just included this in the [[Player#Finite State Tree States]] but I think it is special enough to be it's own state 
- ### Movement State [[Player Movement State]] 
	Bulk of state machine, containt state for ground & air state. 

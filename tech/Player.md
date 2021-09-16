# Player
## Finite State Tree States
- ### Dialogue / Cutscene State
	- Used for taking control away from player during a cutscene or dialogue so they can't move while talking or being talked to (also provides functionality to force inputs onto Nita to make them move wherever)
- ### Sleeping State
	- Used for cutscenes but mainly used as a transition between the player movement state after they die. Before respawning, their state will go to sleeping first to play an animation. I could've just included this in the [[Player#Finite State Tree States]] but  
- ### [[Player Movement State]]

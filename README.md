### Multi game Yaml/config for https://archipelago.gg

# Don't forget to enable plando "items" in your host.yaml file
## [Enabling Plando](https://archipelago.gg/tutorial/Archipelago/plando/en#enabling-plando)


## Trigger options available:

randomize_game_selection:
 - For randomizing what game gets selected

supported_games_only:  
 - Will select only from a list of supported games
   - If enabled this will always randomize the game selection as well

async: 
  - Otherwise known as "long seed", usually just more tasks/bosses and total checks
    - This will only change game settings, not pick specific async games
 
per_game_name: 
 - Picks a name depending on what game gets selected
   - defaults to a standard name if disabled




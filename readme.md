### Multi game Yaml for https://archipelago.gg / [archipelago github](https://github.com/ArchipelagoMW/Archipelago)
With lot of comments explaining how weight, plando, triggers and everything else inside the yaml works

### Last updated for: v0.5.1

# Don't forget to enable plando "items" in host.yaml
## [Enabling Plando](https://archipelago.gg/tutorial/Archipelago/plando/en#enabling-plando)


### Trigger options available:

**supported_games_only:**
 - Will select only from a list of supported games
   - If enabled this will always randomize the game selection as well

**async:** 
  - Otherwise known as "long seed", usually just more tasks/bosses and total checks
    - This will only change game settings, not pick specific async games
 
**per_game_name:** 
 - Picks a name depending on what game gets selected
   - defaults to a standard name if disabled



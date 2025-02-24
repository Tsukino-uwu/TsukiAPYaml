### Multi game Yaml for https://archipelago.gg / [archipelago github](https://github.com/ArchipelagoMW/Archipelago)
WIP.txt & oldyaml.txt contains a lot of comments explaining how weight, plando, triggers and everything else inside yamls works,
but I decided to make the main yaml really basic and simple so its a bit easier to read/understand

### Last updated for: v0.5.1

# Don't forget to enable plando "items" in host.yaml
## [Enabling Plando](https://archipelago.gg/tutorial/Archipelago/plando/en#enabling-plando)


### Trigger options available:

**supported_games_only:**
 - Random from a list of supported games

**async:** 
  - Otherwise known as "long seed", usually just more tasks/bosses and total checks
    - This will still keep a games default settings, but overwrites/replace specific mentioned settings for async
 
**per_game_name:** 
 - Picks a name depending on what game gets selected
   - defaults to a standard name if disabled
   - the name at the top is just a placeholder to avoid errors/syntax issues, all names get changed at the bottom of the yaml



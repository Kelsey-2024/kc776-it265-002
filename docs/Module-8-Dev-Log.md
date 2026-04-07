<!-- Markdown Docs: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax -->
## Name: Kelsey Cordero
### Module: 8

### Date: [04/06/2026]

#### Goals for this Module
- [ ] Transition focus from physical prototype to digital game design
- [ ] Brainstorm room interaction systems for a digital environment
- [ ] Define item, event, and trap mechanics without relying on cards
- [ ] Explore inventory systems and player item limits
- [ ] Begin considering implementation using Unity

#### Progress
- **What I accomplished**:
  - Shifting the design from a physical board game to a digital game concept
  - Decided to replace card-based mechanics with tile based triggers:
    - Event Spaces
    - Item Spaces
    - Trap spaces
  - Began designing how players will interact with rooms in a digital setting
  - Explored different approaches to inventory systems and item limits
  - Considered how randomness like tiles and events should function per game
    
- **Challenges faced**:
  - Determining how players should "open" or interact with rooms in a way that feels engaging and not difficult or annoying
  - Deciding whether to keep randomness consistent or fully procedural (tiles vs events)
  - Balancing item availability so players are not overpowered or under-equipped
  - Translating physical mechanis (cards, tiles) into digital systems without losing gameplay depth
- **Solutions**:
  - Proposed that rooms are revealed through adjacent interaction:
    - Players must move next to a room and trigger an interaction (click or key press)
    - This gives players more control compared to random tile flipping
  - Decided to shift fully to space-based mechanics instead of cards:
    - Landing on a tile triggers an event, item, or trap automatically
  - Designed a hybrid inventory system:
    - Players start with one unique item tied to their character
    - Players can also collect additonal items through exploration
  - Established an item limit:
    - Each player can hold up to 3 items
    - Encourages strategic decision making (keep, discard or use)
  -  <!--Your entry here or N/A if not applicable for this entry-->

#### Learnings
- Digital games allow for more interactive systems compared to physical prototypes
- Removing cards simplifies gameplay and improves pacing in a digital environment
- Inventory limits are essential for maintaining balance and preventing item hoarding
- Player agency (choosing when/how to interact) is more imporant in digital design
-  <!--Your entry here or N/A if not applicable for this entry-->

#### Free Thinking
- **Room Interaction System**
- _Rooms_ :
  - Hidden
  - Revealed when players move adjacent and interact
- _Possible interaction methods_ :
  - Button press, e.g. "E" to open room
  - Automatic reveal when adajacent
- _Some rooms may require_ :
  - Keys
  - Items
  - Multiple players (Such as the exit requires all players)
    
- **Inventory system** :  
-  _Each player_ :
  -  Starts with 1 unique item based on their ability
  -  Can carry up to 3 items total
-  Item types:
  -  Utility (lantern, key tools)
  -  Healing (medkit)
  -  Noise Control (charms)
    
-  **Event System** :
-  Events are triggered by stepping on event tiles
-  Examples:
  -  Gain item
  -  Increase noise
  -  Reveal nearby rooms
  -  Trigger ghost presence

-  **Trap System**
-  Traps are tied to specific tiles
-  Examples:
  -  Movement restriction
  -  Temporary stun
  -  Increased noise
  -  Forced repositioning

-  **Randomization Design**
-  _Rooms_:
  -  Procedurally generated each game
  -  Ensures replayability
-  _Event/Item/Traps_:
-  Two options considered:
  1. Fixed per map
  2. Random per game
-  _Decision_:
-  Use semi-random system:
  -  Room layout will be random
  -  Tile types (events/items/traps) will be randomized within constraints

-  **Digital Horror System**
-  Instead of instant loss:
  -  Noise triggers a monster presence
  -  Monster slowly approaches players
-  Adds:
-  Real-time pressure
-  Continuous tension instead of sudden game over

-  **Unity Implementation Thoughts**
-  _Will use Unity to..._
  -  Create a top-down game
  -  Handle player movement and interaction
  -  Implement tile-based grid system
-  _Systems to build_:
  -  Grid/tile manager
  -  Player controller
  -  Interaction system
  -  Inventory system
  -  Noise system

- Example prompts:
  - n/a

#### Next Steps
- Finalize room interation mechanics (manual vs automatic reveal)
- Design UI for inventoru and noise tracking
- Begin learning Unity basics (movement, input, grid systems)
- Prototype simple top-down movement systems
- Define monster behavior logic for digital version
- Start implementing tile interaction system in Unity

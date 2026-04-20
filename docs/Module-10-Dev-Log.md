<!-- Markdown Docs: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax -->
## Name: Kelsey Cordero
### Module: 10
<!-- Repeat the below as needed-->
### Date: [04/20/2026]

#### Goals for this Module
- [X] Explore Unity and understand basic tools and interface
- [X] Begin planning digital implementation of core mechanics
- [ ] Decide on movement systems (dice based vs. free movement)
- [ ] Define how players interact with rooms in real time

#### Progress
- **What I accomplished**:
  - Installed Unity and explored the editor environment
  - Became familiar with:
    - Scene view
    - Game objects
    - Basic movement concepts
  - Still planning how to implement a grid-based system for player movement
  - Brainstoremed how to transition board game mechanics into a digital format
  - Evaluated whether to keep or remove dice based movement
- **Challenges faced**:
  - Determining whether digital version should remain turn based or become real time
  - Deciding how room interaction should work:
    - Should players stop and explore?
    - Should gameplay pause or continue for others?
  - Understanding how to implement grid movement and player control in Unity
  - Balancing structure (board game rules) with freedom (digital play)
 
- **Solutions**:
  - Decided to move toward a real time exploration system instead of a strict turn based gameplay (I fear that this would ruin room exploration).
  - By removing turn based movement:
    - Players will move freely using keyboard control
    - Creates a smoother and immersive experience.
  - Room interaction will include:
    - Hidden items
    - Traps
    - Event triggers
  - Gameplay will not pause for other players when a player enters a room. This encourages exploration simultaneously and cooperative communication and urgency.  

#### Learnings
- Digital games allow for more flexibility than physical baord games
- Removing dice simplifies player control and improves pacing
- Real time systems create more immersion but requires careful balancing
- Unity uses object-based design, which requires careful planning in terms of components and behaviors.

#### Free Thinking

##### Movement System
- Free movement feels nature than dice roll
- Grid based movement can still be used behind the scenes for structure.
- Players are not locked into turns
- If one player enters a room:
  - Others can help explore or explore elsewhere
##### AI / Monster Concept
- Monster will be controlled by AI so that it moves towards noisy players, patrol areas, and increase tension over time.
- Being that I am no longer using dice for movement, players will not be controlled by AI. 
##### Unity Implementation Plan
- Grid system: Use Unity Tilemap
- Player movement: Need a script for keyboard input
- Interaction: Trigger zons or collision detection
- Noise System: Global variable affecting game state

#### Next Steps
- Implement basic player movement in Unity
- Create a simple grid or tilemap system
- Prototype a basic room with interactable objects
- Begin scripting event triggers
- Design how the monster AI will funtion in real time.

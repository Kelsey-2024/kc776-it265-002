<!-- Markdown Docs: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax -->
## Name: Shadow Grid Studios
### Module: Concept Design & Physical Prototype Planning

<!-- Repeat the below as needed-->
### Date: 01/26/2026

#### Goals for this Module
- [ ] Define the core concept for a cooperative horror board-style game
- [ ] Establish win and loss conditions to avoid luck-based gameplay
- [ ] Design a turn-based flow suitable for multiplayer systems
- [ ] Create a rule-based monster movement system for a physical prototype

#### Progress
- **What I accomplished**:
  - Finalized the main game concept as a cooperative horror exploration game using tile-based rooms.
  - Designed layer objectives including collecting keys, restoring power, and reaching a locked exit.
  - Created a standard turn structure with threat phase, player action phase, enemy movement phase, and pressure escalation.
  - Developed a physical monster AI system using sight range and noise tokens to guide movement and targeting.
  - Outline how puzzles will integrate into the flow without disrupting turn structure.
- **Challenges faced**:
  - Preventing early random tile draws (such as finding the exit immediately) from ending the game too quickly.
  - Designing enemy behavior that feels intelligent without being overly complex for a board-style system.
- **Solutions**:
  - Implemented locked exit mechanics that require completing objectives before escape is possible.
  - Used a priority-based monster movement system that checks visibility first, noise second, and patrol last.

#### Learnings
- Clear rule-based systems can simulate intelligent AI behavior without complex algorithms.
- Turn-based structures make multiplayer synchronization easier when transitioning on digital games.
- Layered objectives create tension and prevent luck from dominating gameplay outcomes.

#### Free Thinking
- Consider introducing different monster types in later iterations that prioritize sound, sight, or darkness differently.
- Explore how player abilities coul interact with noise (e.g., silent movement vs loud sprinting).
- Think about how difficulty could scale by increasing monster speed, sight range, or frequency of threat events.
- Reflect on how the physical prototype directly maps to Unity systems such as AI state machines and event managers.

- Example prompts:
  - "What if the player interactions were asynchronous instead of real-time?"
  - "How could ECS improve performance in this system?"
  - "Does my current design support scalability? How can it improve?"
  
-->

#### Next Steps
- Design a basic tile set and map layout for early physical playtesting.
- Create sample event cards and noise token rules.
- Write a simple rulebook for version 1 of the physical prototype.
- Begin outlinign Unity systems that will correspond to board mechanics (turn manager, AI controller, tile map).

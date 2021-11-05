# Shape Up: Stop Running in Circles and Ship Work that Matters

by Ryan Singer

[https://basecamp.com/shapeup](https://basecamp.com/shapeup)

## Quotes & notes

### Part 1: Shaping

- 2. Principles of Shaping
- 3. Set Boundaries
  - Fixed time, variable scope
  - Raw idea: Requests or feature ideas that are expressed in words and haven't been shaped
  - Appetite: The amount of time we want to spend on the project, as opposed to an estimate.
    - Small Batch: 1-2 weeks. Batch together into the time span of a Big Batch
    - Big Batch: 6 weeks
  - Narrow down the problem definition
  - When we have all three things—a raw idea, an appetite, and a narrow problem   definition—we’re ready to move to the next step and define the elements of a solution.
- 4. Find the Elements
  - Questions to try and answer:
    - Where in the current system does the new thing fit?
    - How do you get to it?
    - What are the key components or interactions?
    - Where does it take you?
  - Design at the right level of abstraction
  - Breadboarding
    - Places: things you can navigate to, like screens, dialogs, or menus that pop up
    - Affordances: things the user can act on, like buttons and fields, interface copy
    - Connection lines: show how the affordances take the user from place to place
  - Fat marker sketches: less fidelity than a wireframe
  - Go from a cloudy idea to a specific approach and a handful of concrete elements. But   still very rough and mostly in outline.
- 5. Risks and Rabbit Holes
  - Questions to ask:
    - Does this require new technical work we’ve never done before?
    - Are we making assumptions about how the parts fit together?
    - Are we assuming a design solution exists that we couldn’t come up with ourselves?
    - Is there a hard decision we should settle in advance so it doesn’t trip up the team?
  - Look for rabbit holes eg. Grouped todos - where do the completed items go?
  - Explicitly declare areas 'out of bounds' to clarify the scope
  - Cut back - flag things as unnecessary and cut it from the core of the project. Can still mention it as a nice-to-have
  - Present to technical experts
    - Ask “is X possible in 6-weeks?”
    - Emphasize that you’re looking for risks that could blow up the project
    - Use to validate the approach or discover problems to use for another round of shaping
  - At the end of this stage, we have the elements of the solution, patches for potential rabbit holes, and fences around areas we’ve declared out of bounds. We’ve gone from a roughly formed solution with potential risk in it to a solid idea that we now hope to bet on in the future.
- 6. Write the Pitch
  - Five ingredients in a pitch
    1. Problem — The raw idea, a use case, or something we’ve seen that motivates us to work on this
      - The best problem definition consists of a single specific story that shows why the status quo doesn't work
    2. Appetite — How much time we want to spend and how that constrains the solution
    3. Solution — The core elements we came up with, presented in a form that’s easy for people to immediately understand
    4. Rabbit holes — Details about the solution worth calling out to avoid problems
    5. No-gos — Anything specifically excluded from the concept: functionality or use cases we intentionally aren’t covering to fit the appetite or make the problem tractable

### Part 2: Betting

- 7. Bets, Not Backlogs
- 8. The Betting Table
  - Six week cycles: long enough to finish something meaningful and short enough to feel the deadline from the beginning.
  - Circuit breaker: cancel projects that don't ship in one cycle by default instead of extending them by default
    - if a project doesn’t finish in the six weeks, it means we did something wrong in the shaping. Instead of investing more time in a bad approach, the circuit breaker pushes us to reframe the problem
- 9. Place Your Bets
  - For existing products, shaping is as described
  - For new products, shaping is adjusted:
    - R&D mode: A phase of building a new product where a senior team spikes the cor features to define the core architecture
    - Production mode: A phase of building a new product where the core architecture is settled and we apply the standard Shape Up process
    - Cleanup mode: The last phase of building a new product, where we don't shape or bet on any particular projects but instead allocate unstructured time to fix whatever is needed before launch

### Part 3: Building

- 10. Hand Over Responsibility
- 11. Get One Piece Done
- 12. Map the Scopes
  - Organize by structure, not by person
  - Scopes: Parts of a project that can be built, and finished independently of the rest of the project (integrated slices). 
  - Don't start by mapping the scopes. Instead start by identifying the obvious tasks, then let the scopes naturally identify themselves from the tasks. Not all tasks will be discovered at teh start. New tasks will also be discovered organically. This is fine and good. -- "You need to walk the territory before you can draw the map"
- 13. Show Progress
- 14. Decide When to Stop
  - Instead of comparing up against the ideal, compare down to Baseline (what customers are doing without the thing we're currently building)
  - Circuit breaker: cancel projects that don't ship in one cycle by default instead of extending them by default. This forces the team to make trade-offs.
  - Constantly cut scope as it grows
  - Scope hammering: Forcefully questioning a design, implementation, or use case to cut scope and finish inside the fixed time box. - Mark nice-to-haves with a `~`
- 15. Move On
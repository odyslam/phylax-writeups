## Lightweight, Agile Management Strategies

### SDLC

I'm a big believer in [Kanban](https://businessmap.io/kanban-resources/getting-started/what-is-kanban) because it is reasonably simple and entirely data-driven.

```mermaid
flowchart LR

Ideation --> Breakdown
Breakdown --> Execution
Execution -->|Spikes| Breakdown
Execution --> Delivery
```

#### Kanban Crash Course

Task management boards have three states: *To Do*, *In Progress*, and *Done*.

The *To Do* column is sorted by priority and constantly groomed. Anyone can look at the board and see what needs done, and grab a new piece of work from the top of the pile when they need a new task assigned. Because everyone is grabbing from the same pile, we avoid creating Key Man risk and specialization.

There cannot be more than N - 1 tasks in `In Progress` at once, where N is the number of people in the working group. This is referred to as the *WIP* limit, and ensures that the team can work at a comfortable pace without becoming overwhelmed, which enhances focus and productivity. If an unplanned work item comes up, a task is created and put into an `Expedite` swimlane.

As each task for a given project is completed, the time required to complete it is tracked. This is called *Cycle Time*. Over time, Cycle Time should trend downward until it reaches a homeostasis, which indicates that the process is working well. It's easy to isolate where things have gone wrong, because there will be giant spikes in the data. Unknowns, dedicated research time, testing, and other commonly neglected bodies of work in software engineering can be budgeted into this flow to ensure they are properly addressed.

Every day, work item state is communicated at a stand-up (synchronously or asynchronously as teams prefer). When a project has been completed, or perhaps at the end of an arbitrary interval of time, a retro is performed to harvest learnings and gather feedback from the team to inform continuous improvement processes.

Operationally speaking, the goal of Kanban is to provide a body of data from which to extrapolate delivery timelines. For example, if a team's average Cycle Time is 2 days, and a breakdown meeting for a new feature produces 10 items, the delivery time for that feature will average 20 days. Using this system, software engineering teams can use data to ascertain a real measure of their own velocity, and schedule feature delivery with confidence.

### Management

I generally subscribe to the tenants outlined in Will Larson's [An Elegant Puzzle](https://lethain.com/elegant-puzzle/):

#### Key Principles
* Prioritize actually finishing things.
* Ensure people know:
  * What they should be working on,
  * Why it is valuable,
  * Definition of done,
  * How to figure out what to work on next.
* Focus resources vs. spreading them out evenly.
* Shift scope rapidly vs. moving people rapidly.
* Make changes, then allow time for them to bake in.
* Create an inclusive organization by providing access to opportunity/resources and enabling people to participate as their authentic selves.
* Reevaluate systems after 1-2 orders of magnitude of growth.
* Work the process, not the exceptions.

### Team-Building

I also generally subscribe to the ideologies outlined in [The Five Dysfunctions of a Team](https://en.wikipedia.org/wiki/The_Five_Dysfunctions_of_a_Team) by Patrick Lencioni:

1) Inattention to Results
* Caused by feelings of status and isolated, individual egos getting priority over the collective state.
* Solved by making collective results clear, attainable, actionable, and significant (see: [SMART Goals](https://www.forbes.com/advisor/business/smart-goals/)).

2) Avoidance of Accountability
* Evidenced by low standards.
* Solved by getting everyone emotionally committed to the same outcomes.

3) Lack of Commitment
* Evidenced by ambiguity.
* Solved by ensuring people feel heard while not aiming for 100% consensus. "Disagree and commit".

4) Fear of Conflict
* Evidenced by Yes-Men, literally no conflict, meandering and endless business workflows or conversations.
* Solved by fostering a culture of honest, constructive ideological exchange.

5) Absence of Trust
* Evidenced by people holding back with each other, failing to understand and open up to one-another.
* Solved by fostering a culture of safety and vulnerability without reprisal (see: [Blameless Culture](https://www.gybe.ca/a-few-words-about-blameless-culture/)).
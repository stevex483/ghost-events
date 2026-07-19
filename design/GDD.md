# Ghost Events

## Game Design Document

**Project:** Ghost Events

**Project Status:** Pre-Production

**Document Version:** 0.1

**Game Version Target:** Minecraft Forge 1.20.1

**Author:** Stevex483

**Last Updated:** 2026-07-19

---

> **This document describes the vision, gameplay philosophy and long-term design goals of Ghost Events.**


---

## Document Status

| Section | Status |
|---------|--------|
| Vision | ✔ Draft |
| Design Philosophy | ✔ Draft |
| Core Experience | ⏳ Not Started |
| Gameplay Loop | ⏳ Not Started |
| Entities | ⏳ Not Started |
| Manifestations | ⏳ Not Started |
| GhostBox | ⏳ Not Started |
| Exorcism | ⏳ Not Started |

---

Table of Contents

1. Vision

1.1 Project Vision

1.2 Design Philosophy

1.3 Engine Philosophy

1.4 Target Audience

1.5 Development Pillars

1.6 What Ghost Events is NOT

2. Core Experience

3. Gameplay Loop

4. Core Systems Architecture

5. Entities

6. Manifestations

7. Equipment

8. Haunted Areas

9. Exorcism

10. Compatibility

11. Roadmap

---

# 1. Vision

## 1.0 Project Vision

Ghost Events is not designed to be another ghost hunting game or a Minecraft adaptation of existing paranormal investigation games.

Its goal is to become the definitive dynamic paranormal storytelling engine for Minecraft.

Instead of asking players to collect predefined evidence or follow scripted sequences, Ghost Events creates believable, unpredictable and cinematic paranormal events that naturally support roleplay, immersive gameplay and video production.

The mod is primarily intended for players and content creators who want to tell their own paranormal stories inside Minecraft.

Every investigation should feel unique.

Every haunted location should develop its own atmosphere.

Every entity should behave according to its own personality and objectives rather than following fixed scripts.

Ghost Events does not try to scare players through constant action.

Instead, it builds tension through uncertainty, atmosphere and intelligent event orchestration.

The objective is to make the player question every sound, every shadow and every unexpected event, without ever being certain that another manifestation will happen.

The mod is designed around emergent storytelling.

Rather than forcing a scenario, it provides the systems required for stories to naturally emerge from gameplay.

Ghost Events does not attempt to replace the creativity of the player.

Instead, it provides intelligent systems capable of generating believable paranormal situations, allowing players and content creators to build their own stories around them.



## 1.1 Project Goals

Ghost Events aims to:

- Create believable paranormal investigations.

- Generate emergent stories instead of scripted scenarios.

- Become the reference paranormal storytelling engine for Minecraft.

- Encourage immersive roleplay and cinematic gameplay.

- Offer a highly configurable experience for creators and players.



## 1.2 Design Philosophy

Ghost Events is built around one simple idea:

The paranormal should never feel scripted.

Players should never be able to predict exactly when, where or how a manifestation will occur.

Instead of creating random events without meaning, the mod simulates paranormal entities with their own behaviour, motivations and preferred manifestations.

Every paranormal event is the consequence of an entity's behaviour, intentions or influence rather than pure randomness.

The objective is not to overwhelm the player with constant activity.

Silence, anticipation and uncertainty are as important as the manifestations themselves.

Fear is created by expectation rather than repetition.

The paranormal should be intelligent rather than random.



## 1.3 Engine Philosophy

Ghost Events is designed as a modular engine rather than a collection of independent features.

The Core provides generic systems responsible for observation, decision making, scheduling and execution.

All future gameplay features should extend these systems instead of replacing them.

The architecture is intentionally designed to remain stable throughout the lifetime of the project.



> ## Ghost Events Core Principle

> **The player should never know whether the next minute will be completely silent...**

> **...or become the most terrifying moment of the entire investigation.**



## 1.4 Target Audience

Ghost Events is primarily designed for:

- Story-driven players

- Roleplay communities

- Horror map creators

- Minecraft machinima creators

- Paranormal investigation roleplay

- YouTube content creators

The mod focuses on creating memorable moments rather than competitive gameplay.

Ghost Events is not intended to be a competitive gameplay experience.

Its primary purpose is to create immersive paranormal narratives that naturally generate memorable moments.



## 1.5 Development Pillars

Every feature added to Ghost Events should reinforce at least one of these principles.

1. The paranormal must feel alive.

Entities make decisions based on their own behaviour rather than scripted sequences.

2. Every investigation tells a story.

The gameplay should naturally generate memorable narratives.

3. Uncertainty creates fear.

Players should never fully understand what will happen next.

4. Atmosphere comes before action.

Silence and anticipation are as valuable as manifestations.

5. The engine comes before the content.

New entities and features should extend the engine without requiring fundamental changes to its architecture.

6. Modularity before complexity.

Every new feature should integrate into the existing architecture without requiring fundamental changes to the Core.



## 1.6 What Ghost Events is NOT

Ghost Events is not designed to be:

- A Phasmophobia clone.

- A simple horror mod focused on jumpscares.

- A scripted adventure map.

- A combat-oriented experience.

- A random event generator.

Instead, Ghost Events focuses on emergent storytelling, believable paranormal behaviour and cinematic investigations.


---

## Project Motto

> "Every paranormal event should make the player ask one question:

> *Did that really just happen?*"

---

## Project Identity

**Ghost Events**

*Dynamic Paranormal Storytelling Engine*

---


# 2. Core Experience

## 2.1 What is a Ghost Events Investigation?

A Ghost Events investigation is not a mission with predefined objectives.

It is an emergent paranormal experience driven by the interaction between the player, the environment and one or more paranormal entities.

The player is free to investigate using any available equipment, explore the haunted location at their own pace and choose how to react to every manifestation.

No investigation follows a fixed script.

Instead, every event is generated by the behaviour of the entities inhabiting the location and by the player's own actions.

The objective is not to "win" the investigation.

The objective is to experience a believable paranormal story.

## 2.2 Player Freedom

Ghost Events does not dictate how an investigation should unfold.

Players decide:

- how long they investigate;

- which equipment they use;

- whether they remain cautious or confront the entity;

- whether they attempt an exorcism;

- whether they leave the location or continue the investigation.

The mod reacts to the player's decisions instead of forcing predefined gameplay sequences.

Every investigation is unique because every player approaches it differently.

Ghost Events is built around contrast.

Long periods of silence make manifestations meaningful.

The absence of paranormal activity is not empty gameplay.

It is an intentional part of the investigation experience.

The tension comes from uncertainty rather than constant action.

## 2.3 Investigation Rhythm

Ghost Events investigations are built around alternating periods of calm and paranormal activity.

Moments where nothing happens are intentionally part of the gameplay.

Silence allows tension to build naturally and makes every manifestation feel meaningful.

The objective is to avoid predictable gameplay loops where paranormal events occur at fixed intervals.

Instead, the pacing should continuously evolve according to the entities' behaviour, the player's actions and the current investigation context.

No two investigations should ever follow exactly the same rhythm.

## 2.4 Building Tension

Fear in Ghost Events is created through uncertainty rather than constant action.

The player should never feel completely safe, but should also never know when the next manifestation will occur.

The Director continuously balances calm periods and paranormal activity to create anticipation.

Unexpected manifestations become memorable because they interrupt moments of apparent normality.

## 2.5 Player Agency

Players are never forced into a predefined sequence of actions.

Ghost Events encourages experimentation.

Players decide how they investigate, which equipment they use, when they take risks and when they decide to leave.

The Director reacts to the player's behaviour instead of forcing scripted progression.

Every decision can influence the investigation in subtle or significant ways.

## 2.6 Emergent Storytelling

Ghost Events does not generate stories.

It generates situations.

Stories emerge naturally from the interaction between the player, the entities and the environment.

Unexpected combinations of manifestations, player decisions and entity behaviour create memorable investigations that cannot be perfectly reproduced.

The objective is to provide players and content creators with authentic paranormal experiences rather than scripted scenarios.

## 2.7 Replayability

Every investigation should remain unpredictable.

Even when revisiting the same haunted location, players should encounter different behaviours, manifestations and pacing.

Randomness alone is not sufficient.

Replayability is achieved through intelligent decision making performed by the entities and the Manifestation Director.

The goal is for players to remember investigations, not scripted events.

## 2.8 Investigation Profiles

Ghost Events supports multiple investigation profiles designed for different styles of gameplay.

Each profile adjusts the behaviour of the paranormal engine rather than changing the gameplay mechanics.

For example, a Story Creator profile may prioritize cinematic pacing, while an Emergent profile allows the Director complete control over the investigation.

Additional profiles may be introduced in future versions to support new types of experiences.

## 2.9 The Unknown

Ghost Events intentionally avoids giving the player complete knowledge of the paranormal.

Players should rarely know:

- how many entities are present;

- which type of entity they are facing;

- why a manifestation occurred;

- whether the entity is hostile or merely observing.

Uncertainty is a fundamental part of every investigation.

The unknown should always feel larger than what the player currently understands.

## 2.10 Investigation Outcomes

Investigations do not have predefined success or failure conditions.

An investigation may end because:

- the player leaves;

- the entity disappears;

- an exorcism succeeds;

- the player is forced to flee;

- the player dies;

- the player decides to continue another day.

Every ending contributes to the story of the investigation.

The objective is not to complete objectives but to experience believable paranormal events.

## 2.11 Creator First Philosophy

Ghost Events is designed with content creation in mind.

Every system should naturally support storytelling, roleplay and cinematic gameplay.

Players should be able to record investigations without requiring scripted events or external intervention.

The Director is designed to generate memorable moments while still leaving complete creative freedom to the player.



# 3. Gameplay Loop

## 3.1 Investigation Flow

A Ghost Events investigation naturally progresses through several phases.

These phases are not predefined objectives or mandatory gameplay sequences.

Instead, they represent the natural evolution of a paranormal investigation.

Players remain completely free to skip, repeat or interrupt any phase according to their own investigation style.

The Manifestation Director continuously adapts the paranormal activity based on the player's behaviour, the haunted location and the entities currently present.

Every investigation should naturally evolve without ever feeling scripted.



## 3.2 Preparation

Every investigation begins before entering the haunted location.

Players prepare their equipment, learn about the location and decide how they intend to approach the investigation.

Depending on their playstyle, players may choose different tools, strategies or objectives before entering the haunted area.

Preparation establishes the context of the investigation without revealing what will actually happen.



## 3.3 Arrival

Upon arriving at the haunted location, players begin observing their surroundings.

The objective is not immediately to find paranormal activity, but to become familiar with the environment.

The atmosphere, architecture and ambient sounds should already contribute to building tension before any manifestation occurs.

At this stage, nothing paranormal is guaranteed to happen.

Silence itself is part of the experience.



## 3.4 Initial Exploration

Players freely explore the haunted location.

They may photograph rooms, inspect objects, search for interesting locations or identify places where investigation equipment could later be installed.

This phase allows players to naturally discover the environment while gradually becoming emotionally attached to the location.

The investigation remains entirely driven by curiosity.



## 3.5 Observation Phase

Observation is a fundamental part of every investigation.

Players may review photographs, monitor surveillance cameras, watch entity detectors or simply remain still while listening to their surroundings.

During this phase, paranormal activity may remain absent for an extended period of time.

These quiet moments intentionally increase anticipation and make future manifestations significantly more impactful.



## 3.6 First Contact

Eventually, the investigation may produce its first undeniable paranormal event.

This first contact can take many different forms.

A distant sound.

A moving door.

An unusual photograph.

A GhostBox response.

A triggered detector.

An unexplained movement captured by surveillance cameras.

The purpose of this phase is not to frighten the player immediately, but to replace uncertainty with suspicion.

The player begins to believe that something may truly be present.



## 3.7 Active Investigation

Once paranormal activity has been confirmed, the investigation becomes more proactive.

Players begin experimenting with different investigation methods.

They may ask questions using the GhostBox, communicate through a Ouija Board, place additional surveillance equipment, revisit suspicious areas or attempt to provoke further manifestations.

The entities observe the player's behaviour and react according to their own personality, motivations and current emotional state.

The investigation becomes a dynamic interaction rather than a sequence of scripted events.



## 3.8 Escalation

As the investigation progresses, paranormal activity may become increasingly intense.

Manifestations become more frequent, more direct or more unpredictable depending on the behaviour of the entities and the player's actions.

However, escalation is never guaranteed.

Some entities may deliberately remain discreet throughout the entire investigation, while others become increasingly hostile over time.

The objective is to create an evolving emotional experience rather than a predictable increase in difficulty.



## 3.9 Resolution

Every investigation eventually reaches a conclusion.

Players may decide to leave the location.

Attempt an exorcism.

Continue searching for answers.

Flee from danger.

Or simply abandon the investigation.

Ghost Events does not impose a single correct ending.

Every investigation concludes according to the choices made by the player and the behaviour of the paranormal entities.



## 3.10 Investigation Outcome

Ghost Events does not define investigations as success or failure.

Instead, every investigation becomes its own story.

Some investigations end peacefully.

Others reveal disturbing truths.

Some entities disappear.

Others remain active.

Players may survive, escape, die or successfully remove the paranormal presence.

Each outcome contributes to the player's personal narrative rather than completing a predefined objective.



## 3.11 Emergent Gameplay

No investigation should ever unfold exactly the same way.

The Gameplay Loop exists as a natural framework rather than a rigid gameplay sequence.

Players create their own investigation style while the Manifestation Director continuously adapts the paranormal activity around them.

Every investigation emerges from the interaction between the player, the haunted location and the entities inhabiting it.

The objective is not to generate random events, but to create believable paranormal stories that naturally emerge through gameplay.


## 3.12 Investigation States

Internally, every investigation evolves through several invisible states.

These states are used by the paranormal engine to determine the overall intensity, pacing and possible manifestations of the investigation.

Typical investigation states include:

- Idle
- Observation
- Suspicion
- Confirmed Activity
- Active Investigation
- Escalation
- Critical Event
- Resolution
- Aftermath

These states are not visible to the player.

Instead, they provide the Manifestation Director with contextual information used to orchestrate believable paranormal activity throughout the investigation.



# 4. Core Systems Architecture

## 4.1 Engine Overview

Ghost Events is built as a modular paranormal simulation engine rather than a collection of independent gameplay features.

Instead of allowing individual systems to directly control paranormal activity, the Core Architecture separates observation, decision making, planning and execution into independent engines.

Each engine has a clearly defined responsibility and communicates with the others through well-defined interfaces.

This separation ensures that new gameplay features can be added without requiring fundamental changes to the existing architecture.

The Core acts as the central nervous system of Ghost Events, coordinating every paranormal event that occurs during an investigation.



## 4.2 Architecture Philosophy

The architecture of Ghost Events follows several fundamental principles.

Every engine should have a single responsibility.

No engine should directly perform the responsibilities of another.

Decision making should remain independent from event execution.

Information should naturally flow between engines without creating unnecessary dependencies.

The architecture is intentionally designed to remain stable throughout the lifetime of the project while allowing continuous expansion through future updates.



## 4.3 Core Layers

Internally, Ghost Events is organized into multiple logical layers.

Each layer transforms information before passing it to the next one.

The overall flow can be summarized as follows:

Player & World

↓

Observation Layer

↓

Decision Layer

↓

Planning Layer

↓

Execution Layer

↓

Minecraft World

Each layer has a specific role and should remain independent from the implementation details of the others.

This layered architecture improves maintainability, scalability and long-term development.



## 4.4 Core Engines

The Ghost Events Core is composed of several specialized engines.

Each engine performs a specific task while collaborating with the others.

The current architecture includes:

• Player Observation Engine

Responsible for collecting information about players, their equipment, actions and investigation behaviour.

• Haunted Area Engine

Responsible for monitoring haunted locations, safe zones, paranormal influence and environmental context.

• Entity Intelligence Engine

Responsible for managing paranormal entities, their personalities, objectives, emotional state and behavioural logic.

• Manifestation Director

Acts as the central decision-making engine.

It determines which paranormal manifestation should occur based on all available information.

The Director never executes manifestations directly.

• Event Scheduler

Responsible for determining when approved manifestations should occur.

It controls pacing, timing and investigation rhythm.

• Manifestation Engine

Responsible for executing paranormal manifestations inside the Minecraft world.

It performs the actions decided by the Director.

• Compatibility Engine

Responsible for detecting and interacting with supported third-party mods.

This engine allows Ghost Events to extend its behaviour when compatible equipment or mechanics are available.



## 4.5 Data Flow

Information continuously circulates through the Core Architecture.

Rather than directly triggering paranormal events, every engine contributes to the decision-making process.

A simplified data flow is illustrated below.

Player

↓

Observation Engine

↓

Manifestation Director

↓

Event Scheduler

↓

Manifestation Engine

↓

Minecraft World

This continuous flow allows paranormal activity to remain reactive, believable and highly configurable.



## 4.6 Decision Making

Ghost Events separates decision making from execution.

The Manifestation Director determines what should happen.

The Event Scheduler determines when it should happen.

The Manifestation Engine determines how it happens inside the Minecraft world.

This separation prevents individual systems from becoming overly complex and allows each engine to evolve independently.



## 4.7 Modularity

Every gameplay feature should integrate into the existing Core rather than bypass it.

New paranormal entities, investigation equipment, manifestations or compatibility modules should extend the architecture without modifying its foundations.

This modular approach allows Ghost Events to grow organically while maintaining a stable Core.



## 4.8 Extensibility

The Core Architecture is intentionally designed for long-term expansion.

Future systems should be able to integrate by extending existing engines rather than replacing them.

Whenever possible, new gameplay mechanics should reuse existing observation, decision making and execution systems.

This philosophy minimizes technical debt while encouraging continuous development.



## 4.9 Multiplayer Considerations

Although Ghost Events is primarily designed around single-player investigations during its initial development, the Core Architecture is built with multiplayer support in mind.

The architecture should remain capable of supporting multiple investigators, shared paranormal events and synchronized entity behaviour in future versions.

Multiplayer support is considered a long-term objective rather than a feature of the first public release.



## 4.10 Future Expansion

The Ghost Events Core is designed to evolve throughout the lifetime of the project.

Future updates may introduce new investigation equipment, additional paranormal entities, advanced AI behaviours, expanded compatibility systems and entirely new gameplay mechanics.

The architecture should allow these additions to integrate naturally without requiring major redesigns of the existing Core.

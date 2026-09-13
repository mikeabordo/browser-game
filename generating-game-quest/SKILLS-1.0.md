---
name: generating-game-quests
description: >-
  Generates a structured, balanced game quest or mission. Use when a user needs to create a new quest, objective, or narrative challenge for a game. Triggers on keywords like "create a quest", "game mission", or "quest idea".
---

# Game Quest Generator

## Instructions

1. **Analyze the Request**: Identify the requested theme, difficulty, and core objective (e.g., fetch, escort, puzzle, combat). If not provided, default to a sci-fi or exploration theme.
2. **Establish the Narrative Context**:
   - Write a brief 1-2 sentence hook explaining why the player must undertake this mission.
   - Define the quest giver (name and a brief personality trait).
3. **Outline the Objectives**: Provide 3 to 4 clear, sequential steps the player must take to complete the quest.
4. **Inject a Twist**: Include one unexpected event, moral choice, or environmental hazard during the quest to prevent it from feeling repetitive.
5. **Define the Rewards**: Specify the loot, experience points, or story progression unlocked upon completion.

## Output Format

Always return the generated quest strictly in the following markdown structure:

### [Quest Name]

**Objective Type:** [Type]
**Quest Giver:** [Name & Trait]

**Narrative Hook:**
[1-2 sentences explaining the stakes]

**Mission Steps:**

1. [Step 1]
2. [Step 2]
3. [Step 3]

**The Twist:**
[Description of the unexpected event]

**Rewards:**

- [Reward 1]
- [Reward 2]

## Example Output

### The Tesseract Anomaly

**Objective Type:** Temporal Puzzle / Retrieval
**Quest Giver:** Agent Mobius (Pragmatic and slightly weary)

**Narrative Hook:**
A localized gravitational anomaly is threatening to stretch the sector into a singularity. You must navigate the shifting time-dilation zones to retrieve the core stabilizing matrix before the system collapses.

**Mission Steps:**

1. Traverse the outer debris field while avoiding pockets of extreme time dilation.
2. Align the three prismatic mirrors to unlock the central containment vault.
3. Retrieve the core stabilizing matrix from the vault pedestal.
4. Escort the station's orange feline mascot, Cherry, who wandered into the vault, back to the airlock safely.

**The Twist:**
Once the matrix is removed, the gravity in the room inverts. The player must navigate the exit sequence walking on the ceiling while protecting the mascot.

**Rewards:**

- 5,000 Cosmic Credits
- Blueprint: Chrono-Stabilizer Mod

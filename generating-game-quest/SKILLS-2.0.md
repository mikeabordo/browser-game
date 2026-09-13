---
name: generating-game-quests
description: >-
  Generates a structured, balanced game quest or mission. Use when a user needs to create a new quest, objective, or narrative challenge for a game. Triggers on keywords like "create a quest", "game mission", or "quest idea".
---

# Game Quest Generator

## Instructions

1. **Analyze the Request**: Identify the requested theme, difficulty, and core objective (e.g., fetch, escort, puzzle, combat). If not provided, default to the genre of the game being developed, or high-fantasy if no game context is available.
2. **Establish the Narrative Context**:
   - Write exactly 2 sentences for the narrative hook. The first sentence establishes the situation; the second raises the stakes.
   - Define the quest giver (name and a brief personality trait in parentheses).
3. **Assign Difficulty & Level**: Select a difficulty tier (Easy, Medium, Hard, or Elite) and a recommended player level range that matches the quest's complexity and combat requirements.
4. **Define the Setting**: Specify the primary location and its atmosphere in one sentence to ground the quest in a concrete environment.
5. **Outline the Objectives**: Provide 3 to 4 clear, sequential steps the player must take to complete the quest. Each step must begin with an action verb (e.g., "Traverse", "Defeat", "Retrieve", "Escort").
6. **Inject a Twist**: The twist must present the player with a meaningful choice that has visible consequences. Describe both the choice AND the two possible outcomes in 2-3 sentences.
7. **Define the Rewards**: Include at least 3 rewards covering: (a) currency and/or XP, (b) a unique item or equipment piece, and (c) a narrative or faction consequence (e.g., reputation gain, story unlock, NPC relationship change).

## Output Format

You MUST format the output exactly as shown below. Use `###` for the quest name. Use `**bold**` for every field label. Use numbered lists (`1.`, `2.`, `3.`) for mission steps. Use bullet points (`-`) for rewards. Do not omit any formatting markers. Do not add fields that are not in this template.

### [Quest Name]

**Objective Type:** [Type]
**Quest Giver:** [Name (Personality Trait)]
**Difficulty:** [Easy / Medium / Hard / Elite]
**Recommended Level:** [e.g., 10-15]
**Setting:** [Primary location and atmosphere in one sentence]

**Narrative Hook:**
[Exactly 2 sentences. Sentence 1 = situation. Sentence 2 = stakes.]

**Mission Steps:**

1. [Step 1 — begins with an action verb]
2. [Step 2 — begins with an action verb]
3. [Step 3 — begins with an action verb]
4. [Step 4 — optional, begins with an action verb]

**The Twist:**
[2-3 sentences: the meaningful choice and its two possible outcomes]

**Rewards:**

- [Currency and/or XP reward]
- [Unique item or equipment piece]
- [Narrative or faction consequence]

## Constraints

- Do NOT reference copyrighted characters, settings, or storylines.
- Do NOT include graphic violence or content inappropriate for a general audience.
- Do NOT generate more than 4 mission steps or more than 4 rewards.
- Do NOT write quest names longer than 5 words.
- Do NOT combine multiple ideas into a single run-on sentence in the narrative hook.
- Do NOT add fields, sections, or formatting that are not specified in the output template above.

## Example Output

### The Tesseract Anomaly

**Objective Type:** Temporal Puzzle / Retrieval
**Quest Giver:** Agent Mobius (Pragmatic and slightly weary)
**Difficulty:** Hard
**Recommended Level:** 18-22
**Setting:** A crumbling orbital station caught in overlapping time-dilation fields, where corridors shift between past and future states.

**Narrative Hook:**
A localized gravitational anomaly is pulling an entire sector toward collapse into a singularity. If the core stabilizing matrix is not retrieved within the hour, the station and everyone aboard will be crushed beyond recovery.

**Mission Steps:**

1. Traverse the outer debris field while avoiding pockets of extreme time dilation.
2. Align the three prismatic mirrors to unlock the central containment vault.
3. Retrieve the core stabilizing matrix from the vault pedestal.
4. Escort the station's orange feline mascot, Cherry, who wandered into the vault, back to the airlock safely.

**The Twist:**
Once the matrix is removed, the gravity in the room inverts. The player must choose: carry Cherry to safety at the cost of dropping the matrix temporarily (risking it being seized by a rival scavenger), or secure the matrix first and hope Cherry can follow on her own. Choosing Cherry earns the crew's loyalty and a bonus reward; choosing the matrix ensures mission success but damages the crew's trust.

**Rewards:**

- 5,000 Cosmic Credits & 4,200 XP
- Blueprint: Chrono-Stabilizer Mod (+20 Temporal Resistance)
- Crew Loyalty: +300 Station Reputation (or -150 if Cherry was left behind)


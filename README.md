# AI Game Development & Testing Assessment

This repository documents my exploration and practical application of generative AI workflows, custom agent skill architecture, and browser-game prototyping for Withcenter, Inc.

---

## 1. Project Overview & AI Study

During this assessment, I focused on treating AI not merely as a conversational tool, but as an integrated development partner. My core learning objectives included:
* **Standardizing Agent Behavior:** Implementing structured AI workflows via the `agentskills.io` standard to ensure predictable, schema-compliant outputs.
* **Prompt Iteration & Edge-Case Handling:** Moving from broad conversational prompts to constrained technical instructions to eliminate hallucinations.
* **AI-Assisted Prototyping:** Leveraging AI tools (Gemini, Codex) to rapidly write, debug, and optimize a cross-platform HTML5 browser game.

---

## 2. Repository Structure

```text
├── agent-skills/
│   └── game-quest-generator/
│       ├── SKILL.md                 # Agent skill definition and constraints
│       ├── example-v1-raw.md        # Initial AI test output
│       └── example-v2-refined.md    # Output after refining the skill prompt
├── game-src/
│   ├── index.html                   # Core game structure
│   ├── style.css                    # Responsive layout and styling
│   └── game.js                      # Game logic, state management, and touch events
└── README.md
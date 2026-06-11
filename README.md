# TechPixel Agent (v1.1) — Bloxd.io Dev Assistant (v1.1)

TechPixel Agent is a specialized, terminal-inspired integrated development environment (IDE) and AI assistant tailored exclusively for **Bloxd.io** modding and scripting via the **WorldCode** framework. Driven by an optimized execution model, it helps creators draft, test, and deploy custom game mechanics up to 10x faster.

<div style="display: flex; overflow-x: auto; gap: 10px; white-space: nowrap; padding-bottom: 10px;">
  <img src="https://github.com/user-attachments/assets/37c4b86f-3a31-421b-bc8b-22bb8d8e9950" width="600" style="flex: 0 0 auto;" />
  <img src="https://github.com/user-attachments/assets/a914c7f9-a3f5-46ed-9c7c-4b5771cfa9d4" width="600" style="flex: 0 0 auto;" />
  <img src="https://github.com/user-attachments/assets/f23f81b5-a8f2-4ec3-b4bb-ab5407dc204d" width="600" style="flex: 0 0 auto;" />
  <img src="https://github.com/user-attachments/assets/87e28a44-b396-40d4-93bb-6e27341eac8a" width="600" style="flex: 0 0 auto;" />
  <img src="https://github.com/user-attachments/assets/93a8a874-5612-4f80-806a-f4a07fc66f83" width="600" style="flex: 0 0 auto;" />
</div>
---

## Complete Feature Breakdown

### Native WorldCode Templates (One-Click Initialization)
The workspace features a grid of pre-configured code boilerplates ready to run or modify instantly:
* **`killstreak.js`**: Generates a kill streak reward system for tracking consecutive player kills and awarding custom scaling rewards.
* **`spawn_entity.js`**: Implements spatial coordinate parsing to spawn entities at a player's exact position dynamically.
* **`team_balance.js`**: Provides server-side auto-balancing algorithms for competitive PvP matchmaking.
* **`shop_gui.js`**: Builds an interactive graphical user interface featuring multiple item slots and support for custom in-game currencies.
* **`api_lookup.ts`**: A dedicated utility to instantly reference, explain, and query the latest Bloxd.io WorldCode API functions.
* **`leaderboard.js`**: Sets up volatile, round-based competitive data tracking that automatically resets at the end of each round.

### Advanced Agent Runtime & Deep Reasoning Controls
Fine-tune how the AI processes your scripts using built-in bottom-bar and menu toggles:
* **Runtime Core Engine**: Powered by the `gpt-4o` model optimized for complex programming and logic debugging.
* **Granular Search Modes**: 
  * `auto`: Automatically scales context depth based on query complexity.
  * `deep`: Conducts exhaustive logical code audits and deeper multi-step reasoning.
  * `balanced`: Strikes an efficient middle ground between rapid generation speed and analytical depth.
* **Research and Plan Modes**: Specialized execution pathways designed to handle long-form analytical research and step-by-step project blueprinting.
* **Extended Thinking and Effort Levels**: Toggle deep reasoning performance with granular control options including low, balanced, and thorough processing tiers.
* **`web:on` (Always-On Web Search)**: An integrated live-sync engine that continuously crawls live game update logs and external repositories during code generation to prevent generic API hallucinations.
* **`memory: active`**: A persistent memory core

### Automated Training and Knowledge Verification
* **Training Submissions**: Submit custom documentation, codebase adjustments, and reference materials directly to the system.
* **Relevance Validation Agent**: An integrated validation checker reviews all incoming training data for quality and relevance, automatically approving and injecting it into the knowledge base upon passing.

### Terminal-Inspired IDE UI Layout
* **Unified Sidebar Explorer**: Includes an organizational system featuring:
  * A dedicated `+ new_conversation()` button to clear scopes and initialize fresh tasks.
  * A `CHATS` repository keeping your workspace clean
* **ASCII Terminal Branding**: Features a distinctive retro matrix/terminal layout displaying the `TECHPIXEL` ASCII block logo upon initialization.
* **User Profile & Cloud Connection Profile**: Features a persistent connection status panel (`TECHPIXEL AI · CONNECTED`) tracking the active developer's profile and credentials securely at the base of the sidebar.

### System Customization and Community Hub
* **Comprehensive Settings Menu**: A highly detailed configuration center to adjust profile properties, memory preferences, interface themes, and system parameters.
* **What's New Center**: A dedicated information portal detailing recent release notes, active patch milestones, and version tracking histories for TechPixel.
* **Contributor Credits**: A visible directory celebrating and acknowledging the dedicated community members and developers who contributed to the project.
  

# 🧠 Beaver Coach Project

This repository houses the tools and structure for the "Beaver Coach" metacognitive puzzle training system. The goal is to train the user in finding the critical, load-bearing structural element of a complex problem, rather than just solving for the final numerical answer.

## 🛠 Core Components

### 🌟 1. The Beaver Coach Skill
The entire coaching routine is managed by the `SKILL.md` file located in the `~/workspace/beaver` directory. This file dictates the 8-step coaching process:
1. **PRESENT** (Puzzle)
2. **WAIT**
3. **PROBE** (Socratic questioning)
4. **REFRAME**
5. **REVEAL** (Solution and Path)
6. **EXTRACT** (Pattern Recognition)
7. **LOG** (History)
8. **ADAPT** (Difficulty Scaling)

### 📚 2. Question Database (`/questions`)
All puzzles are stored as individual Markdown files within the `questions/` directory. This structure allows for robust data mining and graph plotting of user weaknesses.

The index is maintained by `question_index.md`, which lists all active questions.

**File Structure (`[number].puzzle_name.md`):**
Each file contains detailed metadata for a single question:
*   **`id`**: Unique identifier (e.g., MATH-001).
*   **`domain`**: Puzzle category (e.g., Math/quantitative, Logic/deduction).
*   **`difficulty`**: Challenge rating (Easy, Medium, Hard).
*   **`concept`**: The specific academic concept being tested (e.g., Conditional Probability).
*   **`puzzle_text`**: The full problem statement.
*   **`solution_details`**: Step-by-step solution, focusing on the **Load-Bearing Concept**.
*   **`history`**: A log of past attempts and struggles.

## 🚀 Getting Started
To begin a coaching session, load the skill and request the first puzzle.

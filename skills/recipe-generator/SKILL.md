---
name: recipe-generator
description: "Generate 2–4 meal options from available ingredients and ask the user to choose one."
allowed-tools: Read Write
---

# Recipe Generator

Based on the parsed and cleaned ingredient list:

1. Generate **2 to 4** distinct meal options that can realistically be made with those ingredients (plus basic pantry staples like salt, pepper, oil).
2. For each meal option, provide:
   - **Name:** A catchy, appetizing name for the dish.
   - **Description:** 1–2 sentences describing what the dish is like.
   - **Time:** An estimated total time (prep + cook combined).
3. Present the options as a numbered list in this format:

---
**1. [Dish Name]** ⏱ [X mins]
[Short description]

**2. [Dish Name]** ⏱ [X mins]
[Short description]
---

4. End with the question: **"Which one would you like to cook?"**

> ⚠️ **CRITICAL:** Do NOT provide cooking steps or a full recipe at this stage. Wait for the user to make their selection.

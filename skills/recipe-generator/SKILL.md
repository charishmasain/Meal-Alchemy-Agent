---
name: recipe-generator
description: Generate multiple meal options based on available ingredients and ask the user to choose.
---

# Instructions

Based on the parsed and cleaned list of ingredients:
1. Generate 2 to 4 distinct meal options.
2. Ensure the meals use primarily the given ingredients (plus basic pantry staples).
3. For each meal option, include:
   - **Name:** A catchy, appetizing name for the dish.
   - **Short Description:** 1-2 brief sentences describing the dish.
   - **Cooking Time:** An estimated total time (prep + cook).
4. Present the options clearly as a numbered list.
5. End by explicitly asking the user: "Which one would you like to cook?"

**CRITICAL:** DO NOT provide the cooking steps or full recipe yet. Wait for the user's selection.

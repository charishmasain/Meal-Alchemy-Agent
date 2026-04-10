---
name: ingredient-parser
description: "Extract, normalize, and deduplicate ingredients from free-form user input."
allowed-tools: Read Write
---

# Ingredient Parser

When the user provides a list or free-form description of the ingredients they have available:

1. Extract all identifiable food items and ingredients from the input.
2. Normalize names to their singular base form (e.g., "eggs" → "egg", "tomatoes" → "tomato", "cloves of garlic" → "garlic").
3. Remove any duplicate ingredients from the list.
4. Output the final cleaned list as a simple bullet list.
5. Briefly confirm the list to the user before proceeding.

**Example output:**
> Got it! Here's what I found:
> - egg
> - onion
> - tomato
> - garlic
> - olive oil

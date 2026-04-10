---
name: ingredient-parser
description: Extract, normalize, and deduplicate ingredients from user input.
---

# Instructions

When the user provides a list or description of the ingredients they have available:
1. Extract all identifiable food items and ingredients from their input.
2. Normalize the names (e.g., convert "eggs" to "egg", "tomatoes" to "tomato").
3. Remove any duplicate ingredients from the list.
4. Output the final, cleaned list of ingredients to be used for recipe generation.

Keep the output brief and confirm what ingredients you have understood before proceeding to generate recipes.

---
name: recipe-executor
description: "Deliver full cooking instructions for the recipe chosen by the user."
allowed-tools: Read Write
---

# Recipe Executor

Trigger this skill **only after** the user has selected one of the meal options from the `recipe-generator`.

Provide a complete, well-formatted recipe using this exact structure:

---
🍽 **[Dish Name]**

⏱ **Time:** [Prep time] + [Cook time] = [Total time]

🧾 **Steps:**
1. [Step one]
2. [Step two]
3. [Step three]
...
*(Maximum 8 steps. Keep each step clear and beginner-friendly.)*

⚡ **Tips:**
- [1–2 quick tips to improve flavor or technique]

🔄 **Variation:**
- [One simple way to change the flavor profile]

🥄 **Substitutions:**
- [Any easy ingredient swaps if applicable]
---

Keep the language simple and encouraging throughout.

# Building-a-recipe-generator
🍳 Project: AI-Powered Recipe Generator
🎯 Objective
The goal of this project is to create a prompt-based system that generates cooking recipes based on user-provided ingredients. This helps explore the effectiveness of prompt engineering in guiding AI models to produce creative and useful results.

🛠️ How It Works
The user provides a list of ingredients (e.g., "eggs, tomatoes, onions").

The AI is prompted to generate a full recipe including:

Dish name

Ingredients list

Step-by-step instructions

Variations can include specifying cuisine type, dietary restrictions, or meal type.

💡 Sample Prompts
Prompt 1 (Basic):


Create a recipe using the following ingredients: eggs, spinach, and cheese.
Prompt 2 (Guided Style):

Generate a healthy vegetarian dinner recipe using mushrooms, broccoli, and brown rice. Include the cooking time and number of servings.
Prompt 3 (Advanced - Chain-of-Thought):


Step-by-step, guide me through creating a quick Indian breakfast using semolina, mustard seeds, and curry leaves.
✅ Expected Outcome
A curated list of well-crafted prompts that reliably generate structured, accurate, and creative recipes.

Demonstration of prompt engineering skills, including:

Task framing

Output formatting

Use of context and constraints (like cuisine, diet, time)

📂 Repository Structure

recipe-generator/
├── prompts/
│   ├── basic_prompts.txt
│   ├── styled_prompts.txt
│   └── advanced_cot_prompts.txt
├── results/
│   ├── output_sample_1.txt
│   ├── output_sample_2.txt
├── README.md
🚀 Future Enhancements
Build a simple Python interface for ingredient input and recipe output.

Create a web UI using Flask or Streamlit.

Add options for nutrition analysis or AI-generated images.

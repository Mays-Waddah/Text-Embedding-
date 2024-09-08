# Text-Embedding

Overview
This project uses transformer models to generate text embeddings. Below are key components and their roles.

Libraries
transformers: Provides pre-trained transformer models and tools for tokenization.
torch: Handles tensor computations and model operations.
Configuration
Config File: Stores model names and settings separately from code. This allows easy updates and flexibility.
Embeddings
What are Embeddings?: Numerical vectors representing text that capture semantic meaning. Useful for various NLP tasks.
Model Loading
Why Use Model Names?: Loading models using their names from a config file makes it easy to switch models without changing the code.
File Handling
with open(config_path, 'r') as file:: Opens and reads files safely, ensuring they are properly closed.
Tokenizer
Purpose: Converts text into tokens (numerical format) that the model can process.
**Test Cases
Valid Input: Test with standard text.
Empty Text: Ensure the function handles empty strings.
Different Models: Try various models as specified in the config file.
Invalid Model: Check how the function handles incorrect model names.
Long Text: Verify performance with long inputs.

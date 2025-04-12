This project is an intelligent Resume Parser that takes a dataset of resumes (in PDF format), processes and embeds them, and allows users to query them using natural language. The system leverages LLMs (Large Language Models) and LangChain to return structured, meaningful information from resumes.

🚀 Features
Accepts PDF resumes and performs automated parsing.

Uses EDA (Exploratory Data Analysis) to understand resume content.

Converts resumes into vector embeddings for efficient querying.

Supports user queries via an API.

Utilizes LLM (e.g., OpenAI) for natural language understanding.

Parses LLM output and provides final structured results.

Explanation of Components:

Dataset (PDF Resumes): Input resumes to be parsed.

EDA: Exploratory data analysis to extract and understand data.

Embeddings: Transforms resume content into vector format.

User Query + API: Interface for user input.

Prompt Template: Merges resume context with query format.

LLM Chain: Processes prompts using a language model.

Output Parsing: Converts LLM output to structured data.

Final Result: Returns meaningful information to the user.

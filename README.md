This project demonstrates two main functionalities:

Task 1 – Conversation Management:

A Python system to manage chat conversations.

Features include:

Adding messages from different participants (add_mssg).

Truncating history based on the number of turns (truncate_by_turns) or character limits (truncate_by_chars).

Summarizing conversations periodically (summarize_every_k_runs) using a large language model.

This helps in keeping chat history concise and readable, while maintaining a summary of important information.

Task 2 – User Information Extraction:

A Python script to extract structured user information from free-form chat messages.

The system extracts fields like name, email, phone, location, and age from conversational text.

It uses AI-driven JSON extraction to ensure that even informal chat input can be converted into structured data.

Key Features:

Supports multiple users in a chat.

Automatically summarizes conversations to reduce clutter.

Converts unstructured chat input into structured JSON for easy analysis.

Handles truncation by turns or by characters to manage long conversations.

Ready for integration with real-time chat or user data collection pipelines.

Technologies Used:

Python

OpenAI / Groq LLM API (llama-3.1-8b-instant)

JSON for structured data

Google Colab for development and GitHub for version control

Use Case / Real-World Applications:

Customer support chat summarization.

Logging and tracking conversations in educational tools.

Extracting user details from online chat or forms.

Maintaining clean and concise conversation histories for AI agents.

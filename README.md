🤖 Conversational Chatbot with Phi-3-mini-4k-instruct
This project implements a simple conversational chatbot using Microsoft’s Phi-3-mini-4k-instruct, a lightweight, instruction-tuned language model. It is optimized for conversational tasks and can generate helpful, natural-sounding responses with a small footprint.

📜 How it works
The script:

Loads the Phi-3-mini-4k-instruct model and tokenizer from Hugging Face.

Sets up a system prompt to guide the assistant's behavior.

Reads user input in a chat loop, appending each message to the conversation history.

Generates a fluent and coherent bot response using sampling techniques (top_k, top_p, temperature) to produce diverse and engaging answers.

⚙️ Usage
Run the script in a Colab or Kaggle environment. Enter your messages at the >> You: prompt and the bot will respond. Type quit to end the conversation.

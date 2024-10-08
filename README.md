# Conversational Chatbot for Multi-language clients

---

This project implements an AI chatbot using the Groq API. The chatbot takes user input and responds with short answers generated by a large language model. It is designed to handle conversational input in a loop, where the AI assistant gives concise responses based on user queries.

## Features

- Simple interaction with the AI model through the console.
- Ability to handle chat history to provide contextual responses.
- Uses Groq API for generating replies.
- Short and helpful assistant responses.
  
## Prerequisites

Before running the project, ensure you have the following:

- **Python 3.8+**
- A **GROQ_API_KEY** from Groq (set in your environment variables).

### Setting up the API Key

1. Obtain your Groq API key.
2. Set the environment variable `GROQ_API_KEY` by adding it to your shell configuration file (e.g., `.bashrc`, `.zshrc`, etc.):

   ```bash
   export GROQ_API_KEY=your_api_key_here
   ```

   Alternatively, you can set it manually in your terminal before running the program:

   ```bash
   export GROQ_API_KEY=your_api_key_here
   ```

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/daniya-safdar/Simple-AI-Chatbot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Simple-AI-Chatbot
   ```

3. Install the required dependencies:

   ```bash
   pip install groq
   ```

## Usage

Run the script to start the chatbot:

```bash
python chatbot.py
```

The chatbot will wait for your input, and it will respond with short answers based on the AI model’s response. The conversation history is maintained during the session to provide context to the chatbot.

### Exiting the Chat

You can exit the chat by typing `exit` at any point.

## Example Interactions

```bash
You: Hello, how are you?
Assistant: Hello, I'm here to help. How can I assist you today?

You: Tell me about AI.
Assistant: AI refers to the development of machines capable of performing tasks that typically require human intelligence.

You: exit
Ending the chat. Goodbye!
```

### English

```bash
You: Hello, how are you?
Assistant: I'm here to help. How can I assist you today?

You: What is artificial intelligence?
Assistant: Artificial intelligence refers to the simulation of human intelligence in machines.

You: exit
Ending the chat. Goodbye!
```

### Spanish

```bash
You: Hola, ¿cómo estás?
Assistant: Estoy aquí para ayudar. ¿En qué te puedo asistir hoy?

You: ¿Qué es la inteligencia artificial?
Assistant: La inteligencia artificial se refiere a la simulación de la inteligencia humana en máquinas.

You: exit
Ending the chat. ¡Adiós!
```

### Arabic

```bash
You: مرحبًا، كيف حالك؟
Assistant: أنا هنا للمساعدة. كيف يمكنني مساعدتك اليوم؟

You: ما هي الذكاء الاصطناعي؟
Assistant: الذكاء الاصطناعي هو محاكاة الذكاء البشري في الآلات.

You: exit
إنهاء المحادثة. وداعًا!
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you have ideas or suggestions for improvements, feel free to open an issue or create a pull request.

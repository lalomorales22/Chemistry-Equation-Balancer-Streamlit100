# Chemistry Equation Balancer AI

This Streamlit application provides an interactive platform for students to learn about and practice balancing chemical equations. It uses AI models to assist in understanding various types of chemical reactions and provides step-by-step guidance on balancing equations.

## Features

- Interactive chat interface for asking questions about chemical equations and reactions
- Support for multiple AI models (OpenAI and Ollama)
- Focus on specific types of chemical reactions
- Conversation saving and loading functionality
- Token usage tracking
- Customizable AI instructions
- Dark/Light theme options

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/lalomorales22/Chemistry-Equation-Balancer-Streamlit100.git
   cd Chemistry-Equation-Balancer-Streamlit100
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key as an environment variable:
   ```
   export OPENAI_API_KEY='your-api-key-here'
   ```

## Usage

Run the Streamlit app:
```
streamlit run app.py
```

Then open your web browser and go to `http://localhost:8501` to use the application.

## How to Use

1. Enter your name in the text input field.
2. Choose an AI model from the sidebar.
3. Optionally, customize the AI instructions and focus on specific reaction types.
4. Enter a chemical equation or ask a question about balancing in the chat input.
5. The AI will provide explanations, step-by-step guidance, and balanced equations when appropriate.
6. You can save and load conversations using the sidebar options.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

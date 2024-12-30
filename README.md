# LLM Based Tutor

## Overview
LLM Based Tutor is a tool designed to generate detailed explanations for technical questions using OpenAI’s GPT or LLAMA models. It provides a streamlined approach to accessing AI-driven insights and enhancing understanding of complex topics.

## Features
- **Model Integration**: Supports both OpenAI’s GPT models (`gpt-4o-mini`) and LLAMA models (`llama3.2`).
- **Dynamic Output**: Utilizes streaming responses for real-time updates in Jupyter/IPython environments.
- **Environment Setup**: Simplified environment configuration using `.env` for API keys and a `tutor_env.yml` for Conda.
- **Prompt System**: Uses system and user prompts for structured query-response interaction.
- **Customizable Prompts**: Easily change prompts to create a tutor for any other topic.

## Setup
1. Clone the repository.
   ```bash
   git clone https://github.com/emads22/llm-based-tutor.git
   cd llm-based-tutor
2. Create and activate a conda environment using the provided `tutor_env.yml` file:
   ```bash
   conda env create -f tutor_env.yml
   conda activate tutor
3. Ensure that your environment has the required dependencies installed.
4. Create a `.env` file and add your OpenAI API key as `OPENAI_API_KEY`.
5. Run the script using `python main.py`.

## Usage
1. Run the script using `python main.py`.
2. The tool will interactively ask questions and provide explanations using either the GPT or LLAMA model.
3. Results are dynamically displayed in a Jupyter/IPython environment.
4. To create a tutor for a different topic, simply modify the prompts in the `user_prompt` function.

## Contributing
Contributions are welcome! Here are some ways you can contribute to the project:
- Report bugs and issues
- Suggest new features or improvements
- Submit pull requests with bug fixes or enhancements

## Author
- Emad &nbsp; E>
  
  [<img src="https://img.shields.io/badge/GitHub-Profile-blue?logo=github" width="150">](https://github.com/emads22)

## License
This project is licensed under the MIT License, which grants permission for free use, modification, distribution, and sublicense of the code, provided that the copyright notice (attributed to [emads22](https://github.com/emads22)) and permission notice are included in all copies or substantial portions of the software. This license is permissive and allows users to utilize the code for both commercial and non-commercial purposes.

Please see the [LICENSE](LICENSE) file for more details.

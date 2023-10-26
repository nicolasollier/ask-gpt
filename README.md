## README: Simple Chat Assistant with OpenAI

This script creates a basic chatbot interface in the terminal, powered by OpenAI's GPT-3.5 Turbo model.

### Requirements:
- `jq` for JSON parsing.
- `curl` to make API requests.
- An OpenAI account to obtain the API key.

### Setup:
1. Make sure you have `jq` and `curl` installed.
   ```bash
   sudo apt install jq curl
2. Store your OpenAI API key in a file named openai_env.sh inside ~/bin/ or elsewhere safe with the following content:
   ```bash
    export OPENAI_API_KEY='YOUR_API_KEY_HERE'
   

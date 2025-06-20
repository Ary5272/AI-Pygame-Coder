# AI Pygame Coder

This repository contains `ai_pygame_coder_v4.py`, a Python script that uses Google's Gemini Pro AI model to generate complete, runnable Pygame scripts based on natural language descriptions. It also includes an integrated code validator that uses `pylint` to check the generated code for syntax errors before you run it.

## Features

-   **AI-Powered Code Generation:** Describe a game you want to create, and the AI will write the Pygame code for you.
-   **Integrated Validator:** Automatically checks the generated Python code for critical syntax errors, reducing the chance of running a broken file.
-   **Single-File Output:** Creates self-contained Pygame scripts that require no external assets like images or sounds.
-   **Configurable:** Easily set your API key and other model parameters at the top of the script.

## Setup

Before you can run the script, you need to set up your environment.

### 1. Prerequisites

-   Python 3.x installed on your system.
-   A Google Gemini API key. You can get one for free from [Google AI Studio](https://aistudio.google.com/app/apikey).

### 2. Install Dependencies

Open your terminal or command prompt and run the following commands to install the necessary Python libraries:

```bash
pip install google-generativeai
pip install pylint

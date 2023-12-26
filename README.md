# Prompt Engineering with OpenAI API

This project demonstrates the use of the OpenAI API for prompt engineering. It includes Python scripts that interact with 
OpenAI's models generate responses based on various prompts.

## Prerequisites
Before you begin, ensure you have Python installed on your system. You will also need an OpenAI API key, which you can obtain by signing up at [OpenAI API](https://platform.openai.com/api-keys) .


## Install Required Packages

Install the openai package and python-dotenv for environment variable management.

```bash
pip install openai python-dotenv
or
conda install -c conda-forge openai
```

## Set Up Your OpenAI API Key
For security, your OpenAI API key should not be hard-coded in your scripts. Instead, use an .env file to store it.
- Create a file named .env in the root directory of your project.
- Add your OpenAI API key to this file:

```bash 
OPENAI_API_KEY='your-api-key' 
```
Replace your-api-key with your actual OpenAI API key.

###### Please note: Prompt engineering techniques are documented in the [Prompt_Engineering_Techniques.ipynb](https://github.com/sfc-gh-RRadhakr/Prompt_Engineering_Techniques/blob/main/Prompt_Engineering_Techniques.ipynb) file

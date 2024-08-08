# LLM
Basic LLM 

This repository contains scripts demonstrating the use of various large language models (LLMs) for text generation and multimodal tasks. The models used in the scripts include Ollama, Qwen2, and Claude from Anthropic. The scripts showcase how to invoke these models, stream responses, and process multimodal inputs.

Requirements
Ensure you have conda installed. The required Python packages are listed in the requirements.txt file.

Installation
Follow these steps to create a conda environment and install the required packages:
# Create a new conda environment
conda create --name LLM python=3.11 --file requirements.txt

# Activate the environment
conda activate LLM

Script 1: Using Ollama Model
This script demonstrates how to use the Ollama model to generate text. It streams the response and prints it to the console.

Script 2: Using Qwen2 Model
This script shows how to use the Qwen2 model to generate a response based on a prompt. The response is streamed and printed to the console.

Script 3: Using Claude from Anthropic and Multimodal Input
This script demonstrates how to use the Claude model from Anthropic to generate text based on a prompt. It also includes an example of processing a multimodal input, where an image is encoded and sent to the model along with a text query.

Script 4: Using Ollama Model with Image Input
This script demonstrates how to use the Ollama model to process an image input and generate a response.

Script 5: Using Groq Models
This script demonstrates how to use various Groq models to generate responses based on a prompt. The script also measures the latency of the API calls.



Acknowledgements
Langchain
Anthropic
Groq
Feel free to contribute to this project by opening issues or submitting pull requests.

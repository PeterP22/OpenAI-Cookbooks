# Simple Python Agent Workflow by Peter Preketes 

## Overview

This repository contains a Jupyter notebook that demonstrates a simple Python agent workflow using the OpenAI API. The agent is designed to generate Python code based on user queries, execute the code, and validate it using automatically generated test cases.

Originally developed using the Mistral AI API, this project has been ported to utilise the latest OpenAI API, showcasing the flexibility and adaptability of the workflow.

## Features

- Generates Python functions based on user queries using OpenAI's GPT-4o model
- Automatically creates test cases for the generated functions
- Executes and validates the generated code
- Implements a retry mechanism for improved reliability
- Provides detailed logging for debugging and transparency

## Requirements

- Python 3.10+
- OpenAI Python library
- python-dotenv
- Jupyter Notebook

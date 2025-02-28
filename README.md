# llm-sample-application
A sample LLM application using Python and OpenAI API

## Prerequisites
- Python 3.7 or higher
- OpenAI API key

## Installation

1. Clone this repository
2. Install required packages:
```bash
pip install openai
```
3. Create a file named `api-key.secret` in the project root and paste your OpenAI API key into it

## Usage

Run the script with:
```bash
python sample.py
```

The script will:
1. Read your API key from `api-key.secret`
2. Make API calls to OpenAI with predefined prompts
3. Save the results to `input_output_pairs.json`

## License
* MIT license (a permissive license, it puts very few restrictions on reuse)

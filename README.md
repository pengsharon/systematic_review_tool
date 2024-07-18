# Systematic Review Tool

## Overview

This Jupyter Notebook provides a tool to assist with conducting literature reviews, particularly scoping reviews. It leverages OpenAI's GPT-3.5-turbo model to generate search strings and review abstracts based on user-defined objectives and questions.

## Features

- **RIS File Parsing**: Upload and parse RIS files to extract titles and abstracts.
- **Search String Generation**: Generate search strings based on your research objective and questions.
- **Abstract Review**: Evaluate abstracts for inclusion in your literature review using different evaluation strategies.

## Installation

To use this tool, you'll need to have the following Python packages installed:

```bash
pip install openai==0.28
pip install streamlit
pip install pandas openpyxl
pip install chardet
```

## Usage
Load the ipynb notebook and run the cells one-by-one. Once the final cell is run, the UI should pop up with input boxes and selections.

### RIS File Parsing

1. **Upload your RIS file** using the provided file upload widget.
2. **Click the "Parse RIS Texts" button** to extract titles and abstracts.
3. **Download the parsed content** as a text file.

### Generating Search Strings

1. **Provide your research objective and questions**.
2. **Click the "Generate Search Strings" button** to get a list of potential search strings.

### Reviewing Abstracts

1. **Provide your research objective, questions, and additional information** if necessary.
2. **Upload your abstracts** either as a file, or text in the textbox. NOTE: it is recommended to upload as text, as performance is noticeably better.
3. **Select an evaluation strategy** from the provided options (Zero Shot, Chain of Thought, Prompt Chaining, Combo).
4. **Click the "Review Abstracts" button** to get inclusion decisions for each abstract.



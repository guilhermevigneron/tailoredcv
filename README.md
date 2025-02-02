# CV Tailoring Tool

A tool that helps you tailor your CV/resume to specific job descriptions using LLM (Large Language Model) chat and Python. This tool combines the power of AI-driven content optimization with simple document conversion to create targeted, ATS-friendly CVs.

## Features

- Customized prompt for LLM platforms (ChatGPT, Gemini, etc.) to optimize CV content
- ATS (Applicant Tracking System) optimization
- Automatic keyword and skill matching with job descriptions
- Python script to convert plain text to .docx format
- Cross-platform compatibility (Windows, macOS, Linux)

## How It Works

### Step 1: LLM CV Tailoring

1. Copy the provided prompt template from `prompt_template.txt`
2. Replace the placeholders with your CV text and target job description
3. Use the prompt in your preferred LLM chat platform
4. Review and save the generated CV text as `tailored_cv_text.txt`

### Step 2: Convert to DOCX

Use the included Python script to convert your tailored CV text into a formatted Word document.

#### Prerequisites

```bash
pip install python-docx
```

#### Usage

1. Ensure your `tailored_cv_text.txt` is in the same directory as the script
2. Run `text_to_docx_converter.py`
3. Find your formatted CV as `tailored_cv.docx` in the same directory

## Components

### LLM Prompt

The included prompt template guides the AI to:
- Analyze the job description for key requirements
- Match and emphasize relevant skills
- Incorporate job-specific keywords
- Optimize content for ATS
- Maintain your core information
- Provide complete, formatted CV text

### Python Converter

The Python script (`text_to_docx_converter.py`) handles:
- Reading the tailored CV text
- Converting text to proper document format
- Maintaining paragraph structure
- Creating a formatted Word document
- Cross-platform file handling

## Output

The tool generates two files:
1. `tailored_cv_text.txt`: The LLM-optimized CV text
2. `tailored_cv.docx`: The formatted Word document version

## Best Practices

- Always review and edit the LLM-generated content before using
- Ensure all information remains accurate and truthful
- Test the formatted document for ATS compatibility
- Adjust paragraph formatting in the Python script if needed (e.g., using single vs. double newlines)

## Requirements

- Python 3.x
- python-docx library
- Access to an LLM platform (ChatGPT, Bard, etc.)

## Files in this Repository

- `README.md`: This documentation file
- `prompt_template.txt`: The LLM prompt template
- `text_to_docx_converter.py`: Python conversion script
- `requirements.txt`: Python dependencies

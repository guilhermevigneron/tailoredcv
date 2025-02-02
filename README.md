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
- Access to an LLM platform

## Files in this Repository

- `README.md`: This documentation file
- `prompt_template.txt`: The LLM prompt template
- `text_to_docx_converter.py`: Python conversion script
- `requirements.txt`: Python dependencies

## Manual Refinements for Enhanced Human Readability

While the Python script automates the process of tailoring your CV for ATS and applies basic styling for improved human readability, you should always review and manually refine the generated `.docx` file in Microsoft Word (or a compatible word processor) to achieve a truly polished and impactful CV.

### Key Areas to Focus on for Manual Refinement:

### 1. Typography and Font Adjustments
- **Fine-tune Font Choices**: The script sets basic fonts (like Arial). Experiment with slightly different fonts within your chosen professional family (e.g., Arial Narrow, Arial Regular, Arial Bold for headings) for subtle visual distinction and better readability. Ensure you use a maximum of 2–3 fonts for consistency.
- **Adjust Font Sizes and Spacing**: While the script sets initial font sizes, you might want to slightly adjust them based on the content density and overall visual balance. Pay attention to line spacing and character spacing within paragraphs for optimal readability.
- **Emphasis with Bold, Italics, Underline (Use Sparingly)**: 
  - Use bolding to highlight key skills, job titles, company names, and dates.
  - Italics can be used for less critical emphasis, like publication titles or specific details.
  - Avoid underlines, as they can clutter the document and are often associated with hyperlinks.

### 2. Layout and Structure Refinement
- **Column Layouts (Especially for Skills)**: 
  - If you want a two-column layout, particularly for the "Skills" section, the script provides a basic bulleted list. 
  - Manually create columns in Word to arrange skills in a more visually compact and scannable format. Be mindful to keep column layouts relatively simple for ATS compatibility.
- **Section Breaks and Spacing**: 
  - Review the spacing between sections and paragraphs.
  - Add or reduce spacing as needed to create clear visual separation and improve the flow of information. 
  - Use Word's paragraph formatting options for precise control over spacing before and after paragraphs and sections.
- **Visual Hierarchy**: 
  - Ensure a clear visual hierarchy through headings, subheadings, and bullet points.
  - Make sure section headers are distinctly larger and bolder than body text to guide the reader's eye.

### 3. Incorporating Visual Elements (Subtly)
- **Icons for Contact Information**: 
  - Consider adding subtle, professional icons next to your contact details (phone, email, LinkedIn, etc.) in the header. 
  - Use simple, line-based icons that are ATS-friendly.
- **Horizontal Lines for Section Breaks**: 
  - Use thin horizontal lines to visually separate major sections (e.g., between "Summary," "Experience," and "Education"). 
  - Ensure lines are thin and light in color (e.g., light gray) to avoid being too visually dominant.
- **Professional Headshot (Industry/Region Dependent)**: 
  - If a headshot is common or expected in your industry or region, insert a professional, high-quality headshot in the top left or right corner. 
  - Ensure the image is properly sized and doesn't disrupt the ATS-friendly text flow.
- **Conservative Use of Color**: 
  - If desired, use a very limited and conservative color palette (e.g., a single accent color like navy blue or dark gray) for headings, lines, or subtle accents. 
  - Keep the background white for printability and professional appearance.

### 4. Content Review and Proofreading
- **Read Aloud**: Read your entire CV aloud to catch any awkward phrasing, grammatical errors, or typos that you might miss when reading silently.
- **Proofread Carefully**: Thoroughly proofread for spelling and grammar errors. Use Word's spell and grammar check but also manually review since automated tools are not always perfect.
- **Clarity and Conciseness**: Ensure your language is clear, concise, and impactful. Remove any jargon or overly technical terms unless they are directly relevant to the job and industry.
- **Tailoring Check**: Re-read the job description one last time and ensure that your refined CV effectively highlights the most relevant skills and experiences while incorporating key keywords naturally.

### 5. Value Proposition/Summary Section Enhancement
- **Top-Left Focus**:
  - Pay special attention to the top-left section (your "Value Proposition" or "Summary"). 
  - Ensure it is concise, compelling, and immediately grabs the reader's attention. It should clearly articulate your key skills, value, and career goals relevant to the target job.
- **Impactful Language**: Use strong action verbs and quantify your achievements whenever possible in this section to maximize its impact.

---

### Final Note:
The goal of manual refinement is to enhance the visual appeal and readability of your CV for human readers without compromising its ATS compatibility. Subtlety and professionalism are key. Focus on clear structure, consistent styling, and impactful content.

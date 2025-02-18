# Company Brochure Generator

This project uses OpenAI's GPT-4 model to generate company brochures from the contents of their landing pages. The application scrapes the provided URL, extracts the relevant text and title, and then generates a well-formatted brochure in markdown.

## Features

- Scrapes landing pages to extract key content.
- Uses GPT-4 to generate a company brochure for prospective customers, investors, and recruits.
- Outputs the brochure in markdown format for easy viewing and editing.

## Installation

### Prerequisites

- Python 3.7 or higher
- A valid OpenAI API key

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/company-brochure-generator.git
    cd company-brochure-generator
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Create a `.env` file and add your OpenAI API key:
    ```env
    OPENAI_API_KEY=your-api-key
    ```

4. Run the application:
    ```bash
    python app.py
    ```

5. Open the Gradio interface in your browser to start generating brochures.
   
## Usage

1. Enter the company name and landing page URL in the Gradio interface.
2. The application will scrape the page, generate a company brochure, and display it in markdown format.




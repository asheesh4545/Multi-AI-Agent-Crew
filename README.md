# Content Creation Crew

This project demonstrates the use of agents to plan, write, and edit content on a given topic using the CrewAI and LangChain-GROQ libraries. The goal is to automate the content creation process using Large Language Models (LLMs).

## Project Aim

The aim of this project is to create a comprehensive and factually accurate blog post on a specified topic by leveraging the power of LLMs. The process involves three main steps:
1. **Planning**: An agent plans the content based on the latest trends and key information about the topic.
2. **Writing**: Another agent writes the blog post following the plan.
3. **Editing**: Finally, an agent edits the blog post to ensure it aligns with journalistic best practices and the organization's writing style.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.6 or later installed on your local machine.
- An API key from GROQ.

## Installation

1. Clone the repository:
    ```sh
    git clone <your-repo-url>
    cd <your-repo-directory>
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv myenv_crew
    source myenv_crew/bin/activate # On Windows use `myenv_crew\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install crewai langchain_groq python-dotenv
    ```

## Setup

1. Create a `.env` file in the root directory of the project:

2. Inside the `.env` file, add your GROQ API key:
    ```env
    GROQ_API_KEY="your-api-key"
    ```

## Usage

1. Ensure your virtual environment is activated.

2. Run the `app.py` script:
    ```sh
    python app.py
    ```

This script will:
- Initialize agents for planning, writing, and editing content.
- Use the GROQ API for language generation.
- Output the final edited blog post.

## Project Structure

- `main.py`: Main script to run the content creation process.
- `.env`: Environment file to store the GROQ API key.
- `README.md`: This readme file.



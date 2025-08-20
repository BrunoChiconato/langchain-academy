# Foundation: Introduction to LangGraph - LangChain Academy

This repository contains my notes, exercises, and projects developed during the "Foundation: Introduction to LangGraph" course from LangChain Academy. The goal is to apply the concepts learned about LangGraph, a powerful framework for building agentic and multi-agent applications.

[![Status](https://img.shields.io/badge/Status-In%20Progress-blue)](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY)

## Table of Contents

- [About the Course](#about-the-course)
- [Technologies Used](#technologies-used)
- [Environment Setup](#environment-setup)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Course Content](#course-content)

## About the Course

The "Foundation: Introduction to LangGraph" course teaches the fundamentals of building robust and controllable workflows with AI agents. It covers everything from creating simple graphs to implementing memory, human-in-the-loop interaction, and deployment. This repository serves as my practical logbook throughout this learning journey.

## Technologies Used

This project utilizes a range of technologies from the AI and Python ecosystem:

-   **Python 3.11+**
-   **LangChain & LangGraph**: The core for building agents and graphs.
-   **OpenAI API**: For access to language models.
-   **LangSmith**: For debugging and monitoring workflows.
-   **Tavily API**: For web search functionalities.
-   **Jupyter Notebooks**: For experimenting and developing exercises.
-   **uv / Poetry**: For package and dependency management.

## Environment Setup

Follow the steps below to set up the development environment locally.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/BrunoChiconato/langchain-academy.git
    cd langchain-academy
    ```

2.  **Create a virtual environment and install dependencies:**
    Using `uv` or another modern environment manager is recommended. The dependencies are listed in the `pyproject.toml` file.
    ```bash
    # Example with uv
    uv venv
    source .venv/bin/activate
    uv pip install -e .
    ```

3.  **Set up environment variables:**
    Create a `.env` file in the project root and add the following keys. Obtain your keys from the respective platforms.
    ```env
    OPENAI_API_KEY="your-key-here"
    LANGSMITH_API_KEY="your-key-here"
    TAVILY_API_KEY="your-key-here"
    ```

## Usage

The exercises and projects are organized within the `app/src/` directory. Each file or subdirectory corresponds to a specific module or lesson from the course, making it easy to navigate and track progress.

To run an exercise, navigate to the corresponding file and execute it with Python, ensuring the virtual environment is activated.

## File Structure

The project is organized with the following structure to keep course artifacts separate from configuration code:

```
.
├── app
│   ├── langgraph.json
│   └── src
│       └── agent
│           ├── **init**.py
│           └── m1\_l2.py
├── pyproject.toml
├── README.md
└── uv.lock
```

- **`app/`**: Contains the source code for the exercises.
  - **`src/agent`**: Modules and scripts for each lesson.
- **`pyproject.toml`**: Project definition and dependency file.

## Course Content

This repository will follow the complete course structure, divided into the following modules:

-   **Module 1: Introduction**
-   **Module 2: State and Memory**
-   **Module 3: UX and Human-in-the-Loop**
-   **Module 4: Building your Assistant**
-   **Module 5: Long-term Memory**
-   **Module 6: Deployment**

*This list will be updated as I progress.*

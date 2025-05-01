# Actuarial Data Analysis Tutorial with LLM Assistance

This tutorial demonstrates how to effectively use Large Language Models (LLMs) like GitHub Copilot or Cursor in actuarial data analysis. The tutorial focuses on mortality data analysis, which is fundamental to many actuarial calculations in Global Risk Management.

## Prerequisites

- Python 3.8 or higher
- Jupyter Notebook
- An LLM assistant (GitHub Copilot or Cursor)
- `virtualenv` (can be installed via `pip install virtualenv`)

## Setup Instructions

1. Clone this repository:

```bash
git clone https://github.com/marcNY/Tutorial-LLM-data-analysis-for-actuaries.git
cd tutorial_dta_analysis
```

2. Set up a virtual environment:

You can use either `virtualenv` (recommended) or `venv`:

Using `virtualenv`:

```bash
# Install virtualenv if you haven't already
pip install virtualenv

# Create virtual environment
virtualenv venv

# Activate the virtual environment
# On macOS/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate
```

Alternative using `venv`:

```bash
# Create virtual environment
python -m venv venv

# Activate the virtual environment
# On macOS/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate
```

3. Install required packages:

```bash
# Make sure your virtual environment is activated
pip install -r requirements.txt
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `llm_actuarial_life_expectancy_tutorial.ipynb` in your browser.

## Tutorial Structure

The tutorial covers:

- Setting up the analysis environment
- Loading and exploring mortality data
- Creating meaningful visualizations
- Performing mortality analysis
- Using LLMs effectively in the analysis workflow
- Best practices for LLM-assisted actuarial analysis

## Key Learning Points

- How to structure your analysis workflow with LLM assistance
- Techniques for mortality data analysis
- Creating effective visualizations
- Statistical analysis of mortality trends
- Best practices for using LLMs in actuarial work

## Target Audience

This tutorial is designed for actuaries in Global Risk Management who want to:

- Learn how to leverage LLMs in their data analysis workflow
- Improve their efficiency in handling mortality data
- Enhance their analytical capabilities with modern tools

## Note

While this tutorial uses synthetic data for demonstration purposes, the techniques can be applied to real-world mortality datasets. Always ensure to verify results and maintain professional skepticism when using LLM-generated code or analysis.

To deactivate the virtual environment when you're done:

```bash
deactivate
```

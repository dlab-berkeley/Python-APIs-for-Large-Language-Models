# D-Lab Python APIs for Large Language Models Workshop

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](http://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-APIs-for-Large-Language-Models&urlpath=lab%2Ftree%2FPython-APIs-for-Large-Language-Models%2F) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-APIs-for-Large-Language-Models/HEAD) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials for D-Lab's Python APIs for Large Language Models Workshop. 

## Prerequisites
We recommend attending [Python Fundamentals](https://github.com/dlab-berkeley/Python-Fundamentals) prior to this workshop.

You will also need a free [OpenRouter](https://openrouter.ai) account and API key. OpenRouter lets you call many different LLMs through one interface, and its free tier does not require a credit card. Sign up before the workshop, generate an API key under Settings -> API Keys, and save it somewhere safe. Part 1 walks through this in more detail.

Check out D-Lab’s [Workshop Catalog](https://dlab-berkeley.github.io/dlab-workshops/) to browse all workshops, see what’s running now, and review prerequisites.

## Workshop Goals

In this hands-on workshop, you will learn how to use Python to call LLM APIs and get structured responses for research applications. By the end, you'll be able to integrate LLMs into your social science research workflow to classify data, extract insights, and analyze content at scale. You'll walk away with best practices for LLM integration in research projects, example scripts for common research tasks, and the confidence to begin incorporating AI into your own research workflow.

## Learning Objectives

After this workshop, you will be able to:

- **API Setup & Authentication:** Understand how LLMs are hosted and accessed, and configure access to an LLM provider using OpenRouter.
- **Chat Completions & Prompting:** Construct requests to the `chat/completions` endpoint, manage conversation history and system prompts, and use zero-shot and few-shot prompting to get consistent results.
- **Structured Output:** Use JSON mode and Pydantic models to guarantee responses in a predefined format for tasks like sentiment classification, theme extraction, and content coding.
- **Tool Calling:** Give an LLM access to Python functions so it can retrieve data and take actions as part of a research workflow.

This workshop does not cover the following:

- Advanced prompt engineering. This is covered in [Prompt Engineering](https://github.com/dlab-berkeley/prompt-engineering).
- A technical understanding of GPT-like models. This is covered in [Python GPT Fundamentals](https://github.com/dlab-berkeley/Python-GPT-Fundamentals).

## Workshop Structure

The workshop is split into four parts. Each notebook in the `lessons` folder has a matching notebook in the `solutions` folder with the challenges filled in.

1. `1_Introduction_to_LLM_APIs.ipynb`: LLMs as a research tool, how LLMs are hosted, and making your first API call through OpenRouter.
2. `2_Chat_Completions_and_Prompting.ipynb`: The `chat/completions` endpoint, message history, system prompts, and zero-shot vs. few-shot prompting.
3. `3_Structured_Output.ipynb`: JSON mode, JSON schemas, and Pydantic models for guaranteed response formats.
4. `4_Tool_Calling.ipynb`: Defining tools, the tool-calling loop that lets the model run Python functions, and a final challenge building a narrative standardization agent.

## Installation Instructions

Before attending the workshop, you should install Python and Jupyter to your computer. If you need help, please submit a [consulting request](https://dlab.berkeley.edu/consulting/submit-consulting-request) with D-Lab prior to the start of the workshop.

Anaconda is software that allows you to run Python and Jupyter notebooks on your computer. Installing Anaconda is the easiest way to make sure you have all the necessary software to run the materials for this workshop. Complete the following steps:

1. [Download and install Anaconda (Python 3 distribution)](https://www.anaconda.com/products/individual). Click "Download" and then click 64-bit "Graphical Installer" for your current operating system. 
2. Download the materials in this repository:

* Click the green "Code" button in the top right of the repository information.
* Click "Download Zip".
* Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

3. Optional: if you're familiar with `git`, you can instead clone this repository by opening a terminal and entering `git clone https://github.com/dlab-berkeley/Python-APIs-for-Large-Language-Models.git`.

4. Install the Python packages used in the workshop by opening a terminal in the repository folder and running `pip install -r requirements.txt`.

## Run the code

Now that you have all the required software and materials, you need to run the code:

1. Open the Anaconda Navigator application. You should see the green snake logo appear on your screen. Note that this can take a few minutes to load up the first time.

2. Click the "Launch" button under "Jupyter Lab" and navigate through your file system to the `Python-APIs-for-Large-Language-Models` folder you downloaded above.

3. Navigate to the `lessons` folder.

4. Open `1_Introduction_to_LLM_APIs.ipynb` to begin.

5. Press Shift + Enter (or Ctrl + Enter) to run a cell.

Note: if you are having trouble accessing the Downloads/Desktop folder from Anaconda Navigator, [check out this post](https://docs.anaconda.com/free/navigator/troubleshooting/) or [submit a consulting request](https://dlab.berkeley.edu/consulting/submit-consulting-request) to get help!

## Is Python not working on your laptop?

If you do not have Anaconda installed and the materials loaded on your workshop by the time it starts, we *strongly* recommend using the UC Berkeley Datahub to run the materials for these lessons. You can access the DataHub by clicking this button:

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](http://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-APIs-for-Large-Language-Models&urlpath=lab%2Ftree%2FPython-APIs-for-Large-Language-Models%2F)

The DataHub downloads this repository, along with any necessary packages, and allows you to run the materials in a Jupyter notebook that is stored on UC Berkeley's servers. No installation is necessary from your end - you only need an internet browser and a CalNet ID to log in. By using the DataHub, you can save your work and come back to it at any time. When you want to return to your saved work, just go straight to [DataHub](https://datahub.berkeley.edu), sign in, and click on the `Python-APIs-for-Large-Language-Models` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in Binder, which is another cloud-based option. Click this button:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-APIs-for-Large-Language-Models/HEAD) 

Note: Using Binder, you unfortunately cannot save your work.

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use Python for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Other D-Lab Python Workshops

Here are other Python workshops offered by the D-Lab:

### Basic competency

* [Python Fundamentals](https://github.com/dlab-berkeley/Python-Fundamentals)
* [Python Data Wrangling](https://github.com/dlab-berkeley/Python-Data-Wrangling)
* [Python Data Visualization](https://github.com/dlab-berkeley/Python-Data-Visualization)
* [Geospatial Fundamentals in Python](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-Python)

### Intermediate/advanced competency

* [Python Text Analysis](https://github.com/dlab-berkeley/python-text-analysis)
* [Python Machine Learning](https://github.com/dlab-berkeley/python-machine-learning)
* [Python Deep Learning](https://github.com/dlab-berkeley/python-deep-learning)

# Contributors

* Sohail Khan
* Tom van Nuenen
* Pratik Sachdeva


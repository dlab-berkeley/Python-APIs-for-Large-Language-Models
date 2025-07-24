# D-Lab Python APIs for Large Language Models Workshop

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](http://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-APIs-for-Large-Language-Models&urlpath=lab%2Ftree%2FPython-APIs-for-Large-Language-Models%2F) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-APIs-for-Large-Language-Models/HEAD) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials for D-Lab's Python APIs for Large Language Models Workshop. 

### Prerequisites
We recommend attending [Python Fundamentals](https://github.com/dlab-berkeley/python-fundamentals) prior to this workshop.

Check D-Lab's [Learning Pathways](https://dlab-berkeley.github.io/dlab-workshops/python_path.html) to figure out which of our workshops to take!

## Workshop Goals

In this hands-on workshop, you will learn how to use Python to call LLM APIs and get structured responses for research applications. By the end, you'll be able to integrate LLMs into your social science research workflow to classify data, extract insights, and analyze content at scale. You'll walk away with best practices for LLM integration in research projects, example scripts for common research tasks, and the confidence to begin incorporating AI into your own research workflow.

## Learning Objectives

After this workshop, you will be able to do:

- **API Setup & Authentication:** Configure access to an LLM provider using OpenRouter for research projects.
- **API Call Formatting:** Understand the differences between chat and completion endpoints, construct proper request formats, handle parameters like temperature and max tokens, and manage conversation context.
- **Structured Output:** Design prompts that return consistent JSON responses for tasks like sentiment classification, theme extraction, content coding, and demographic categorization.
- **Integration & Error Handling:** Parse API responses into Python objects, implement retry logic for failed requests, manage rate limits and costs when processing research datasets.

This workshop does not cover the following:

- Prompt engineering. This is covered in [Prompt Engineering](https://github.com/dlab-berkeley/prompt-engineering).
- A technical understanding of GPT-like models. This is covered in [Python GPT Fundamentals](https://github.com/dlab-berkeley/Python-GPT-Fundamentals).

## Installation Instructions

Before attending the workshop, you should install Python and Jupyter to your computer. If you need help, please submit a [consulting request](https://dlab.berkeley.edu/consulting/submit-consulting-request) with D-Lab prior to the start of the workshop.

Anaconda is software that allows you to run Python and Jupyter notebooks on your computer. Installing Anaconda is the easiest way to make sure you have all the necessary software to run the materials for this workshop. Complete the following steps:

1. [Download and install Anaconda (Python 3.9 distribution)](https://www.anaconda.com/products/individual). Click "Download" and then click 64-bit "Graphical Installer" for your current operating system. 
2. Download the materials in this repository:

* Click the green "Code" button in the top right of the repository information.
* Click "Download Zip".
* Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

3. Optional: if you're familiar with `git`, you can instead clone this repository by opening a terminal and entering `git clone https://github.com/dlab-berkeley/Python-Fundamentals.git`.

## Run the code

Now that you have all the required software and materials, you need to run the code:

1. Open the Anaconda Navigator application. You should see the green snake logo appear on your screen. Note that this can take a few minutes to load up the first time.

2. Click the "Launch" button under "Jupyter Lab" and navigate through your file system to the `Python-Fundamentals` folder you downloaded above.

3. Navigate to lessons -> Fundamentals-I

4. Open the `01_Jupyter_and_Python.ipynb` to begin.

5. Press Shift + Enter (or Ctrl + Enter) to run a cell.

Note: if you are having trouble accessing the Downloads/Desktop folder from Anaconda Navigator, [check out this post](https://docs.anaconda.com/free/navigator/troubleshooting/) or [submit a consulting request](https://dlab.berkeley.edu/consulting/submit-consulting-request) to get help!

## Is Python not working on your laptop?

If you do not have Anaconda installed and the materials loaded on your workshop by the time it starts, we *strongly* recommend using the UC Berkeley Datahub to run the materials for these lessons. You can access the DataHub by clicking this button:

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](http://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-APIs-for-Large-Language-Models&urlpath=lab%2Ftree%2FPython-APIs-for-Large-Language-Models%2F)

The DataHub downloads this repository, along with any necessary packages, and allows you to run the materials in a Jupyter notebook that is stored on UC Berkeley's servers. No installation is necessary from your end - you only need an internet browser and a CalNet ID to log in. By using the DataHub, you can save your work and come back to it at any time. When you want to return to your saved work, just go straight to [DataHub](https://datahub.berkeley.edu), sign in, and you click on the `Python-Fundamentals` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in Binder, which is another cloud-based option. Click this button:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-APIs-for-Large-Language-Models/HEAD) 

Note: Using Binder, you unfortunately cannot save your work.

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

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
Sohail Khan
Pratik Sachdeva
Tom van Nuenen

**Provide a list of contributors here, with links to their webpages (D-Lab or
private).**

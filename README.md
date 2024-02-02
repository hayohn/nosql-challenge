# nosql-challenge

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)

## Overview

Provide a brief overview of the project, its goals, and the problem it aims to solve.

## Setup

1. Clone the repository.
2. Install dependencies.
3. Import data to MongoDB.
4. Set up the environment.

Include any additional setup steps necessary for your project.

### Importing Data

Copy the terminal command used to import data into MongoDB.

```bash
mongoimport --db uk_food --collection establishments --file establishments.json --jsonArray

### Usage

This project includes Jupyter Notebooks that facilitate the exploration and analysis of food hygiene ratings data using MongoDB and PyMongo. Follow these steps to effectively use the provided notebooks:

1. Clone the Repository

Clone the project repository to your local machine using the following command in your terminal or command prompt:

git clone https://github.com/your-username/your-repository.git

2. Set Up Environment

Ensure that you have the necessary dependencies installed. You may use a virtual environment to manage dependencies. Install the required packages using:

pip install -r requirements.txt

3. Import Data

Use the provided terminal command to import the establishments data into MongoDB. Replace establishments.json with your data file if necessary.

mongoimport --db uk_food --collection establishments --file establishments.json --jsonArray

4. Open Jupyter Notebooks

Launch Jupyter Notebooks using the following command:

jupyter notebook

Navigate to the notebooks directory and open the relevant notebook (e.g., NoSQL_setup_starter.ipynb or NoSQL_analysis_starter.ipynb).

5. Execute Code Cells

Run each code cell sequentially by pressing Shift + Enter. The notebooks are designed to guide you through the exploratory analysis, database setup, and answer specific questions.

Feel free to modify the code, explore additional queries, or adapt the notebooks to suit your needs.

6. Exploratory Analysis

Explore the provided notebooks for detailed analysis of the food hygiene ratings dataset. Execute code cells to find answers to specific questions or address analytical tasks.

Remember to save your work if you make changes or additions to the notebooks.

Note

** Ensure that you have MongoDB installed and running on your local machine or specify the appropriate MongoDB connection details within the notebooks.




# Programming for Data Analytics (PFDA) Assignments Repository

**by Finbar Dennehy**

This repository primarily contains four Jupyter Notebooks. Each notebook represents a weekly assignment submission for the 'Programming for Data Analytics' module, part of the HDip in Science in Data Analytics at ATU.

## Repository Contents (Assignments) ##

- `assignment2-weather.ipynb` plots the temperature ("dryBulbTemperature_Celsius") over time, using data from `weatherreadings1.csv`.
- `assignment03-pie.ipynb` creates a pie chart of peoples' email domains using [email domain data](https://drive.google.com/uc?id=1AWPf-pJodJKeHsARQK_RHiNsE8fjPCVK&export=download)
- `assignment_5_risk.ipynb` simulates 1,000 individual battle rounds in Risk (3 attackers vs. 2 defenders) and plots the results. The program is extended to simulate a full series of rounds for armies of arbitary sizes, until one side is wiped out.
- `assignment_6_Weather.ipynb` plots the temperature and windspeed using data from [Knock Airport weather data](https://cli.fusio.net/cli/climate_data/webdata/hly4935.csv).
- `requirements.txt` included in the repository for easy installation, it contains required Python libraries.
- `.gitignore` file using the Python, Windows and Mac OS gitignore templates.

## Purpose

The purpose of this repo is to demonstrate ability in the following:

1. Representing Data.

2. Plotting and using the appropriate plot types.

3. Reading, writing and manipulating data in Pandas.

4. Using Regular Expressions.

5. Generating Random Data.

6. Working with dates and times in Pandas.

## Getting Started

You can run the Jupyter notebooks either locally on your machine or directly in the cloud using [GitHub Codespaces](https://github.com/features/codespaces).

### Option 1: Running Locally

#### Prerequisites

- [Anaconda](https://www.anaconda.com/products/distribution) (recommended) or Python installed on your machine.
- [Visual Studio Code](https://code.visualstudio.com/) with the Jupyter extension.

#### Steps

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/fdennehy/pfda-assignments
   cd your-repo-name
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter notebooks:
   - Open the notebooks in VS Code.
   - Select the appropriate Python interpreter to run the notebook.

### Option 2: Running in GitHub Codespaces

1. Open the repository on GitHub.
2. Click the Code button and select Codespaces.
3. Create a new Codespace or open an existing one.
4. Once the environment is ready, open the notebooks and start running the cells.

## Requirements

The following Python libraries are required to run the notebook:

- pandas

A `requirements.txt` file is included in the repository for easy installation.

## Get Help

Read the comments provided within the Jupyter Notebook and look up official Python documentation for further usage guidance.

## Contribute

Developers are welcome to fork this repo and continue to develop and expand upon it as they wish.

## Author

I'm currently undertaking the HDip in Science in Computing in Data Analytics on a part time basis at ATU

I have over ten years' experience in capital markets consultancy and have spent the past few years working on software delivery and customer success. I am undertaking this program to better understand our clients, who are predominantly data scientists and data engineers.

## Acknowledgements

Special thanks to my lecturer on the Programming for Data Analytics module, Andrew Beatty, from whom I acquired the skills necessary to put this project together.
# Instructions
## Install using requirements.txt
1. Download and install [Python](https://www.python.org/downloads/).
2. Download [this repository](https://github.com/amirwesthoff/python-bts-requests-analysis) from github, or, open a terminal and run `git clone https://github.com/amirwesthoff/python-bts-requests-analysis.git`
3. Navigate to the downloaded folder in the terminal (Windows shortcut: navigate to the `python-bts-requests-analysis` folder in Windows Explorer, type `cmd` in the path bar.)
4. Run `pip install -r requirements.txt`

## To perform analysis on requests
1. Run `python req-analysis.py`

This will process all .xslx files in the requests folder and generate (and overwrite) output.csv and output.xslx. If you don't have output.csv and output.xlsx closed before running this command, your operating system will present an error message.

## To run the local web application
1. Run `python application.py`

This will run a web application with predefined graphs/diagrams and use output.csv as its data.
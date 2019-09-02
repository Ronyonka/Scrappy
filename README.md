# Scrappy
##### Date of Current Version (September 2nd,2019)

## Description
A simple Python script that scraps wikipedia articles (heading and paragraphs) and creates a pdf file.

## Setup/Installation Requirements


### Prerequisites
You need the following to work on the project: -
* Python (version 3+) 
* pip 
* venv 
* git

### Clone the repo and check into the project folder

- `git clone https://github.com/Ronyonka/scrappy`
- `cd scrappy`

### Create and activate the virtual environment

- `$ python3 -m venv venv`
- `$ source venv/bin/activate`


### Install the dependencies found in the  requirements.txt file

```bash
pip install -r requirements.txt
```


### Run the script in the terminal

```bash
python3.6 manage.py 'Hurricane_Dorian'
```
replace 'Hurricane_Dorian' with any wikipedia article name from its url. A pdf should be found in the project folder

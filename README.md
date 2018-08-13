
# tool

## Introduction
 This project is aimed to build a network of tools. The tools vary from simple document conversion tools to real time advice tools. Users will be able to add new tools and interact socially with each other.

## Requirements

Python 3 and django 1.11

## Installation

### Setup the virtual environment
```
 virtualenv venv
 cd venv
 source bin/activate
```

### Clone the project
```
git clone  https://github.com/OpenGenus/tool.git
cd tool
pip install -r requirements.txt
```



### Install other dependencies
- #### Installing pandoc on Ubuntu
	- Install LaTeX: `sudo apt-get install texlive-full`
	- Install pandoc:  `sudo apt-get install pandoc`





## Running on localhost

In `settings.py` change DEBUG to True.
Before running the app make sure to migrate and run collectstatic
```
python manage.py makemigrations
python manage.py migrate

python manage.py collectstatic

```
now run using *python manage.py runserver*

```
## Extra Requirements For some Tools

- #### Installing wkhtmltopdf on windows
	- by default the project contained a folder named wkhtmltopdf it will work without installations
	
- #### Installing wkhtmltopdf on lunix
	- you could download a version  from  here `https://wkhtmltopdf.org/downloads.html`
	 after that replace the folder wkhtmltopdf with your wkhtmltopdf folder you need to have an executable file inside the bin folder 
	 so take care 
   






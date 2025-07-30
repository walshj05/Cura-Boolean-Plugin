# Cura Boolean Plugin
by. Jonathan Walsh
## Overview
Plugin to use 3d meshes as a cutting, union, or intersection tool.

Works similarly to the eraser (support blocker) tool, but allows users to import stl files and use them as a cutting tool, create a union, or only print where the meshes intersect.

## Installation

### Windows

1. Download the plugin files (usually a folder containing `__init__.py` and other Python files).
2. Open Cura.
3. Go to **Help > Show Configuration Folder**.
4. In the opened folder, navigate to the `plugins` directory. If it doesn't exist, create it.
5. Copy the plugin folder into the `plugins` directory.
6. Restart Cura. The plugin should now be available.

### Mac

1. Download the plugin files.
2. Open Cura.
3. Go to **Help > Show Configuration Folder**.
4. In Finder, open the `plugins` directory inside the configuration folder. Create it if it doesn't exist.
5. Copy the plugin folder into the `plugins` directory.
6. Restart Cura to activate the plugin.

## Development Onboarding
In order to contribute to this project, non-direct contributers are encouraged to create a fork of the repository, and pull from upstream frequently. Then make pull requests to the main repository from their fork.

It is recommended that developers use a virtual environment to install all required libraries and packages seperately from their system version of python.

### Repo Setup:
**Note: it is recommended that developers use VSCode in order to have an easier time debugging and following dev cycles...**

**For the sake of simplicity, I will be explaining the onboarding process as if you are using VSCode.**

1. Clone reposiory locally, and open repository in VSCode.
2. Create a virtual environment using `python3 -m venv .venv`, and activate the virtual environment using `source .venv/bin/activate`
3. Install all required packages and libraries with `pip install -r requirements.txt`
4. **(Bonus but helpfuk)** Install the pylint plugin from Microsoft in the VSCode Extensions Tab.

### Learn About Libraries Used
If you aren't familiar with some of the libraries used for this project, look through the `BackgroundInformation` directory to find links to documentation as well as annotated notes for key features. 
# test-package-creation-2

Lecture on setting up project as pakage and uploading to pypi using project.toml file
We will be able to convert the entire project into pakage and we will be able to move it / distribute from one place to another

# Step by step guide

1. conda create -p testpackage2 python==3.12
2. conda activate testpackage2/
3. Make file requirements.txt
4. write library name inside to install eg langchain
5. pip install -r requirements.txt
6. create setup.py and add code in it given by sir krishnaik
7. create pyproject.toml and copy krish code in it
8. create src folder and in src make **init**.py file
9. write -e . in requirements.txt (-e . in requirements.txt is responsible for triggring source.py)
10. pip install -r reqirements.txt
11. You would see that SamplePRoject.egg-info folder means that entire pakage got created

### Folder structure for end to end project

Folder -> src -> **init**.py

**init**.py will make the folder src as package and from this you will be able to import anything anywhere

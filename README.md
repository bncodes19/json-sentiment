# Requests, JSON, and basic NLP with spaCy

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

* (Question 1) Lyrics printed: 1 pt
* (Question 1) File created and submitted with notebook: 1 pt
* (Question 2) Correct polarity reported: 1 pt
* (Question 2) Question answered thoughtfully: 1 pt
* (Question 3) Function defined as specified: 1 pt
* (Question 3) Song lyrics retrieved and stored in separate files (0.5 pts/song): 2 pts
* (Question 4) Polarity scores printed (with appropriate label containing song title, .25 pts/song): 1 pt
* (Question 4) Questions answered thoughtfully: 2 pts


## Dependencies
This project requires a few libraries that must be downloaded. These are: **spacy, spacytextblob, and requests**

Store these libraries in the requirements.txt file in the project repository:
```
spacy
spacytextblob
requests
```

Next, install the packages in the terminal with:
```
python3 -m pip install -r requirements.text
```
Then freeze the requirements.txt file:
```
python3 -m pip freeze > requirements.txt
```
An additional step is required after installing these libraries to download a model from spacy. This command can be run in the terminal:
```
python3 -m spacy download en_core_web_sm
```

This project also uses **json**, but this library do not need to be installed via requirements.txt as they are part of Python's standard library as a built-in module.
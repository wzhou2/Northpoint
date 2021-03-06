# Northpoint

Goldfish Storytelling - collaborative story telling websites here verified users are able to contribute to a story, only with the last edit of another contributor as the context. A user can only contribute to a story once and can view the entire story once it has contributed to it.

## Getting Started

1. Clone this repo with either ssh or http.
```
$ git clone git@github.com:wzhou2/Northpoint.git
or 
$ git clone https://github.com/wzhou2/Northpoint.git
```
2. Open your virtual environment
```
$ . <name_of_vEnv>/bin/activate
```
3. Run the app.py file with python
```
$ python app.py
```
4. Access the website by going to http://127.0.0.1:5000/ on any browser.

### Dependencies

What things you need to install the software and how to install them:
* Python version - 3.6.6
* Virtual Environment 
* Flask
* Wheel
* Time

Time required requested permission to be used for this assignment.
Our team used the Time module to fetch the current time when a user submits an edit 
or creates a story. This information is used to keep track of the order of edits and
is display when searching for stories using the search option. 
(Read more [here](https://docs.python.org/3/library/time.html) at the official documentation)

### Installing

Installing virtual environment, flask, and wheel.
```
$ python -m venv <name_of_vEnv>
$ . <name_of_vEnv>/bin/activate
(<name_of_vEnv>) $ pip3 install flask
(<name_of_vEnv>) $ pip3 install wheel
```
### Contributors
* Hui Min Wu
* Thomas Zhao
* Wei Wen Zhou
* Tania Cao Su


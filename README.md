# GeoDev SWE Interview

## Why an assignment for our interview?

The GeoDev team wishes to give every aspiring team member a fair chance to show off their skills. Traditionally, coding interviews test how hard students study, but they fail to test how good someone is at the actual job. This assignment walks students through a full-stack codebase where students are given the opportunity learn, have fun, and accomplish a real GeoLab task.

## Prerequisites

1. Basic understanding of Python (i.e. intro to cs, intro to data science, or self-taught)
2. A recent version of [Node JS](https://nodejs.org/en/) installed on your computer
3. An installation of `Python 3.7 or newer`.
    - [download](https://www.python.org/ftp/python/3.10.4/python-3.10.4-macos11.pkg) for macOS
    - [download](https://www.python.org/ftp/python/3.10.4/python-3.10.4-amd64.exe) for Windows.
4. An installation of git (Windows Only).
    - [Download](https://github.com/git-for-windows/git/releases/download/v2.35.1.windows.2/Git-2.35.1.2-64-bit.exe) for Windows.
5. A code editor like [VSCode](https://code.visualstudio.com/) (Optional)

When you have completed these steps, try running the following commands in a terminal (or Command Prompt if Windows):

```
npm --version
git --version
python3 --version
```

![](https://github.com/jacobsomer/GeoDev-SWE-Interview/blob/master/images/Image.png)

## Getting Started

If you ran the above commands successfully, `cd` into the folder where you would like to store the project. Here is an example:

```
cd Documents
git clone https://github.com/jacobsomer/GeoDev-SWE-Interview.git
cd GeoDev-SWE-Interview
```
## Running the Flask server
Once you are in the `GeoDev-SWE-Interview` folder on terminal, run the following commands

```
python -m ensurepip --upgrade
pip install Flask
cd server
set FLASK_APP=index
flask run
```
`set FLASK_APP=index` may cause an error if you are using a different terminal than CMD (ex. bash, fish, powershell). If that is the case, please read the [docs](https://flask.palletsprojects.com/en/2.1.x/cli/) for the right command.
If you have done everything right. You should see something like this:
```
 * Serving Flask app "index"
 * Environment: index
 * Debug mode: off
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
Feel free to open `http://127.0.0.1:5000/` in Chrome or safari once you have gotten to this step. You should see something like this:
```
{"direction":"S","speed":3}
```
## Running the React frontend
Open up a separate terminal and `cd` back into the `GeoDev-SWE-Interview` folder (same folder where you ran `git clone https://github.com/jacobsomer/GeoDev-SWE-Interview.git`). Run the following commands:
```
cd client
npm install
npm start
```
You should see a web page open up on your browser. Go to task 1 and begin. Good luck!

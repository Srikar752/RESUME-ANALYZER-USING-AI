<div align="center">
  <h1>AI RESUME ANALYZER</h1>
  <p>A Tool for Resume Analysis, Predictions and Recommendations</p>

## About the Project

<div align="center">
    <p align="justify"> 
      A tool which parses information from a resume using natural language processing and finds the keywords, cluster them onto sectors based on their keywords. 
      And lastly show recommendations, predictions, analytics to the applicant / recruiter based on keyword matching.
    </p>
</div>

## Scope

i. It can be used for getting all the resume data into a structured tabular format and csv as well, so that the organization can use those data for analytics purposes

ii. By providing recommendations, predictions and overall score user can improve their resume and can keep on testing it on our tool

iii. And it can increase more traffic to our tool because of user section

iv. It can be used by colleges to get insight of students and their resume before placements

v. Also, to get analytics for roles which users are mostly looking for

vi. To improve this tool by getting feedbacks

## Tech Stack

<details>
  <summary>Frontend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/HTML">HTML</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS">CSS</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/JavaScript">JavaScript</a></li>
  </ul>
</details>

<details>
  <summary>Backend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://www.python.org/">Python</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.mysql.com/">MySQL</a></li>
  </ul>
</details>

<details>
<summary>Modules</summary>
  <ul>
    <li><a href="https://pandas.pydata.org/">pandas</a></li>
    <li><a href="https://github.com/OmkarPathak/pyresparser">pyresparser</a></li>
    <li><a href="https://pypi.org/project/pdfminer3/">pdfminer3</a></li>
    <li><a href="https://www.nltk.org/">NLTK</a></li>
  </ul>
</details>

<!-- Features -->

## Features

### Client: -

- Fetching Location and Miscellaneous Data

  Using Parsing Techniques to fetch

- Basic Info
- Skills
- Keywords

Using logical programs, it will recommend

- Skills that can be added
- Predicted job role
- Course and certificates
- Resume tips and ideas
- Overall Score
- Interview & Resume tip videos

### Feedback: -

- Form filling
- Rating from 1 – 5
- Show overall ratings pie chart
- Past user comments history

## Requirements

### Have these things installed to make your process smooth

1. Python (3.9.12) https://www.python.org/downloads/release/python-3912/
2. MySQL https://www.mysql.com/downloads/
3. Visual Studio Code **(Prefered Code Editor)** https://code.visualstudio.com/Download
4. Visual Studio build tools for C++ https://aka.ms/vs/17/release/vs_BuildTools.exe

## Setup & Installation

To run this project, perform the following tasks

Download the code file

Create a virtual environment and activate it **(recommended)**

Open your command prompt and change your project directory to `AI-Resume-Analyzer` and run the following command

```bash
python -m venv venvapp

cd venvapp/Scripts

activate

```

Downloading packages from `requirements.txt` inside `App` folder

```bash
cd../..

cd App

pip install -r requirements.txt

python -m spacy download en_core_web_sm

```

After installation is finished create a Database `cv`

And change user credentials inside `App.py`
connection = pymysql.connect(host='localhost',user='root',password='root@MySQL4admin',db='cv')

Go to `venvapp\Lib\site-packages\pyresparser` folder

And replace the `resume_parser.py` with `resume_parser.py`

which was provided by me inside `pyresparser` folder

`Your set-up and installation is finished`

I hope that your `venvapp` is activated and working directory is inside `App`

Run the `App.py` file using

```bash
streamlit run App.py

```

## Known Error

If `GeocoderUnavailable` error comes up then just check your internet connection and network speed

## Usage

- After the setup it will do stuff's automatically
- You just need to upload a resume and see it's magic
- Try first with an example resume uploaded in `Uploaded_Resumes` folder

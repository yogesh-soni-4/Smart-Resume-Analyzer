

# Smart Resume Analyser App
Smart Resume analyzer is a web application that uses  NLP to scan the resume and extract the essential information like name, mail id, skill, domain etc. to generate a score of the resume based on its content and hence providing the tips to improve the score. 


![image](https://user-images.githubusercontent.com/112860792/222917991-1bc3f7d2-9d9b-47d4-a298-54a634f01d42.png)


## Source
- Extracting user's information from the Resume, I used [PyResparser](https://omkarpathak.in/pyresparser/)
- Extracting Resume PDF into Text, I used [PDFMiner](https://pypi.org/project/pdfminer/).

## Features
- User's & Admin Section
- Resume Score
- Career Recommendations
- Resume writing Tips suggestions
- Courses Recommendations
- Skills Recommendations
- Youtube video recommendations

## Usage
- `App.py` is the main Python file of Streamlit Web-Application. 
- `Courses.py` is the Python file that contains courses and youtube video links.
- `Uploaded_Resumes` folder is contaning the user's uploaded resumes.
- `Classifier.py` is the main file which is containing a KNN Algorithm. 

## Screenshots

## User side
![sc1](https://user-images.githubusercontent.com/112860792/222917808-88657507-3b2f-4982-bc22-44fda527518a.png)

## Admin Side
![sc2](https://user-images.githubusercontent.com/112860792/222917818-ab4f6b6e-47f8-49c4-871c-a40e8df3c4b1.png)



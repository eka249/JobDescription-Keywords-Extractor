# JD_Keywords_Extractor
JD_Keywords_Extractor aims to extract important keywords (topics) from any given job description posted online for better search engine optimization (SEO) using Topic Modeling techniques. It can also be used to build a Resume Screening Tool where any given resume would be matched against the topics extracted from JD_Keywords_Extractor.

### Dataset:
Dataset used for building this model was obtained from Kaggle @ https://www.kaggle.com/madhab/jobposts 

### Instruction to containerize the application:

- Build the image using the following command -
$ docker build -t jobs-indicator-app:latest .

- Run the Docker container using the following command -
$ docker run -d -p 5000:5000 jobs-indicator-app
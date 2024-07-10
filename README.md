# Movie Recommendation System

### Description   
> A machine learning model to recommend movies based on a user's preferences by analyzing movie metadata. 

### Workflow
>1) Data Loading and Preprocessing: Merged movie and credits datasets, handled missing values, and extracted relevant columns. 
>2)Feature Extraction: Converted genres, keywords, cast, and crew into a list format using ast.literal_eval. Kept only the top 3 actors and directors.  
>3) Text Processing: Combined the overview, genres, keywords, cast, and crew into a single 'tags' column for each movie. Removed spaces within tags to ensure consistency.
>4) Vectorization: Applied CountVectorizer to convert text data into numerical vectors, considering up to 5000 features and removing English stop words.
>5) Similarity Calculation: Used cosine similarity to measure the similarity between movie vectors.
>6) Recommendation Function: Implemented a function to recommend movies based on the cosine similarity scores.  

### Libraries used
>Nltk  
>TfidfVectorizer  
>Sklearn  
>Numpy  
>Pandas  
>Streamlit  


 
To use the web app, download the zip, extract it and run the below commands  
>1)'pip install -r requirements.txt' to install required libraries  
>2)'streamlit run app.py' to host application in local host
 

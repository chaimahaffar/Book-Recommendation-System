<h1>Book Recommendation System</h1>

<h2>Description</h2>
This project involves developing a system that recommends books to users based on their reading preferences. The system uses collaborative filtering and content-based filtering techniques to suggest books tailored to individual tastes. By analyzing user behavior, ratings, and book metadata, it provides personalized recommendations, enhancing the user experience and encouraging reading engagement.
<br />

<h2>Technologies Used</h2>
- <b>Python</b>  
- <b>Pandas</b> (for data manipulation)  
- <b>Scikit-learn</b> (for implementing machine learning algorithms)  

<h2>Environments Used</h2>
- <b>Jupyter Notebook</b> (for development and testing)  
- <b>jupiter </b> (for model training with large datasets)  

<h2>Project Workflow</h2>

<h3>1. Data Collection and Preprocessing</h3>
<p>
The dataset includes user ratings, book metadata (title, author, genre, description), and user behavior. Preprocessing involves cleaning the data, handling missing values, and standardizing formats for efficient analysis.
</p>

<h3>2. Feature Engineering</h3>
<p>
The system extracts key features from the dataset:
- **User-Book Ratings Matrix**: Used for collaborative filtering.  
- **Book Descriptions**: Processed with **TF-IDF** to create vectors for content-based filtering.  
- **Genre Encoding**: Encoded to enhance recommendation quality.  
</p>

<h3>3. Recommendation Models</h3>
<p>
The system integrates two types of recommendation techniques:
- **Collaborative Filtering**: Suggests books based on similar user preferences using **KNN** or matrix factorization.  
- **Content-Based Filtering**: Recommends books with similar metadata, leveraging **cosine similarity** on TF-IDF vectors of book descriptions.  
</p>


<h2>Evaluation</h2>
<p>
The system is evaluated using:
- **Precision@k**: Measures the relevance of the top-k recommendations.  
- **Recall@k**: Evaluates the proportion of relevant recommendations retrieved.  
- **RMSE (Root Mean Square Error)**: Used to assess the accuracy of predicted ratings in collaborative filtering.  

Performance metrics indicate the system's effectiveness in generating accurate and personalized book suggestions.
</p>

<p align="center">
  Example Evaluation: <br/>
  <img src="https://i.imgur.com/mxtYWrP.png" height="60%" width="60%" alt="Evaluation Metrics"/><br />
</p>

<h2>Results</h2>

<h3>1. Recommendations Based on User Similarity (Figure 19)</h3>
<p>
The system generates recommendations by analyzing user behavior and identifying similar users. Books that are highly rated by users with similar preferences are recommended. This approach ensures that the suggestions are aligned with the reading habits and interests of the individual user.
</p>

<p align="center">
  Example of Recommendations (User Similarity): <br/>
  <img src="https://i.imgur.com/TKfkmuD.png" height="60%" width="60%" alt="User Similarity Recommendations"/><br />
</p>

<h3>2. Recommendations Based on Item Similarity (Figure 20)</h3>
<p>
Using content-based filtering, the system identifies books with similar metadata (e.g., genre, description) to those the user has previously rated or interacted with. This method highlights books that share characteristics with the user’s favorites, expanding their discovery of similar content.
</p>

<p align="center">
  Example of Recommendations (Item Similarity): <br/>
  <img src="https://i.imgur.com/9MsERy9.png" height="60%" width="60%" alt="Item Similarity Recommendations"/><br />
</p>

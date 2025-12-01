<h1 align="center">📚 Book Recommendation System</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Powered-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Manipulation-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Scikit--learn-ML-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Jupyter%20Notebook-Development-red?style=for-the-badge" />
</p>

---

<h2>Description</h2>

<p>
This project involves developing a system that recommends books to users based on their reading preferences. The system uses collaborative filtering and content-based filtering techniques to provide personalized recommendations by analyzing user behavior, ratings, and book metadata, enhancing the user experience and encouraging reading engagement.
</p>

---

<h2>Technologies Used</h2>

<table>
  <thead>
    <tr>
      <th>Technology</th>
      <th>Purpose</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Python</b></td>
      <td>Programming language for system development</td>
    </tr>
    <tr>
      <td><b>Pandas</b></td>
      <td>Data manipulation and preprocessing</td>
    </tr>
    <tr>
      <td><b>Scikit-learn</b></td>
      <td>Implementing machine learning algorithms</td>
    </tr>
    <tr>
      <td><b>Jupyter Notebook</b></td>
      <td>Development and testing environment</td>
    </tr>
  </tbody>
</table>

---

<h2>Environments Used</h2>
<ul>
  <li><b>Jupyter Notebook</b> – Interactive development and testing</li>
  <li><b>Jupyter</b> – Model training with large datasets</li>
</ul>

---

<h2>Project Workflow</h2>

<h3>1. Data Collection and Preprocessing</h3>
<p>
The dataset includes user ratings, book metadata (title, author, genre, description), and user behavior. Preprocessing involves cleaning data, handling missing values, and standardizing formats for efficient analysis.
</p>

<h3>2. Feature Engineering</h3>
<ul>
  <li><b>User-Book Ratings Matrix</b>: Used for collaborative filtering.</li>
  <li><b>Book Descriptions</b>: Processed with TF-IDF to create vectors for content-based filtering.</li>
  <li><b>Genre Encoding</b>: Encoded to enhance recommendation quality.</li>
</ul>

<h3>3. Recommendation Models</h3>
<ul>
  <li><b>Collaborative Filtering</b>: Suggests books based on similar user preferences using KNN or matrix factorization.</li>
  <li><b>Content-Based Filtering</b>: Recommends books with similar metadata, leveraging cosine similarity on TF-IDF vectors of book descriptions.</li>
</ul>

---

<h2>Evaluation</h2>
<p>
The system is evaluated using:
<ul>
  <li><b>Precision@k</b> – Measures relevance of top-k recommendations</li>
  <li><b>Recall@k</b> – Proportion of relevant recommendations retrieved</li>
  <li><b>RMSE</b> – Accuracy of predicted ratings in collaborative filtering</li>
</ul>
Performance metrics indicate effectiveness in generating accurate and personalized recommendations.
</p>

<p align="center">
  <img src="https://i.imgur.com/mxtYWrP.png" height="60%" width="60%" alt="Evaluation Metrics"/><br/>
  <em>Example of Evaluation Metrics</em>
</p>

---

<h2>Results</h2>

<h3>1. Recommendations Based on User Similarity</h3>
<p>
The system generates recommendations by analyzing user behavior and identifying similar users. Books highly rated by similar users are suggested.
</p>

<p align="center">
  <img src="https://i.imgur.com/TKfkmuD.png" height="60%" width="60%" alt="User Similarity Recommendations"/><br/>
  <em>Recommendations based on user similarity</em>
</p>

<h3>2. Recommendations Based on Item Similarity</h3>
<p>
Content-based filtering identifies books with similar metadata to those previously rated by the user, helping discover similar content.
</p>

<p align="center">
  <img src="https://i.imgur.com/9MsERy9.png" height="60%" width="60%" alt="Item Similarity Recommendations"/><br/>
  <em>Recommendations based on item similarity</em>
</p>

---

<h2>Features</h2>
<ul>
  <li>Personalized book recommendations</li>
  <li>Collaborative and content-based filtering integration</li>
  <li>Accurate evaluation with Precision@k, Recall@k, and RMSE</li>
  <li>Supports large datasets and interactive exploration</li>
</ul>

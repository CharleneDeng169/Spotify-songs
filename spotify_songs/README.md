<h1>Project: Spotify songs Classification</h1>

<h2>Description</h2>
Our project aims to develop the best classification model through model comparisons with the main objective of identifying the key factors that influence a song's popularity. By analyzing a dataset containing audio-related statistics for the top 2000 tracks on Spotify from 2000 to 2019, we can classify a song's popularity based on its features.
Understanding the key factors that contribute to a song's popularity can have significant implications for artists and companies in determining preferred styles or genres, making informed decisions about song acquisition or publication. By developing a robust classification model, we aim to provide valuable insights into the music industry and enhance decision-making processes.
<br />


<h2>Algorithms Used</h2>

- <b>K-nearest neighbors</b> 
- <b>Extreme gradient boost</b>
- <b>Random Forest</b>
- <b>logistic regression</b> 
- <b>Super Vector Classification</b>

<h2>Evaluation Measurement </h2>

- <b>Accuracy</b> 
- <b>Precision</b>
- <b>Recall</b>

<h2>Results</h2>
<p align="center">
<br/>
<img src="https://i.imgur.com/0MCsrCk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Considering the overall evaluation metrics of accuracy, precision, recall, and F1 Score, Xgboost and Random Forest showed better performance, while KNN and Logistic had relatively lower scores. That's about what we expected. Random Forest and Xgboost exhibit better performance in terms of overall evaluation metrics. This can be attributed to their ensemble learning approach, which combines multiple weak learners to form a strong learner, allowing them to handle noise and generalize well. Additionally, the use of decision trees in both models enables them to capture non-linear relationships and interactions among features, making them suitable for complex data patterns. Furthermore, the ability to assess feature importance helps understand why these models perform well by capturing the contributions of important features. Finally, through parameter
tuning, both models can be optimized to adapt better to the data, further improving their predictive accuracy.

<h1>Exploratory Analysis of Student Academic Performance</h1>


<h2>Description</h2>
<p>
This project investigates the academic performance of students through exploratory data analysis (EDA) and classification modeling. Using a dataset of over 30,000 student records with attributes related to demographics, socio-economic factors, and activities, the project aims to identify correlations and potential predictors of student success in Math, Reading, and Writing. The analysis utilizes EDA for insight discovery and a K-Nearest Neighbors (KNN) classifier to predict performance based on specific features.
</p>

<h2>Dataset</h2>
<ul>
  <li><b>Students Exam Scores: Extended Dataset</b></li>
  <li>Attributes include:
    <ul>
      <li><b>Demographics:</b> Gender, ethnic group, parental education</li>
      <li><b>Socio-economic indicators:</b> Lunch type, weekly study hours</li>
      <li><b>Activity-based attributes:</b> Test preparation, sports participation</li>
      <li><b>Scores:</b> Math, Reading, Writing</li>
    </ul>
  </li>
</ul>
<p>The dataset is available on <a href="https://www.kaggle.com/datasets/desalegngeb/students-exam-scores?select=Expanded_data_with_more_features.csv">Kaggle</a>.</p>

<h2>Project Structure</h2>
<ol>
  <li><b>Data Preprocessing</b>
    <ul>
      <li>Addressed missing data with random imputation while preserving the ratio of categories.</li>
      <li>Encoded categorical variables using one-hot encoding.</li>
      <li>Scaled features using z-scores for consistent model performance.</li>
    </ul>
  </li>
  <li><b>Exploratory Data Analysis (EDA)</b>
    <ul>
      <li>Visualized the distribution and correlation of academic scores across various student attributes.</li>
      <li>Examined attributes with notable relationships to performance, such as parental education and test preparation.</li>
    </ul>
  </li>
  <li><b>Hypothesis Testing</b>
    <ul>
      <li>Investigated the impact of sports on academic performance using hypothesis testing with simulations.</li>
      <li>Concluded that sports participation did not have a statistically significant effect on academic scores.</li>
    </ul>
  </li>
  <li><b>Classification Model</b>
    <ul>
      <li>Implemented a K-Nearest Neighbors (KNN) classifier.</li>
      <li>Evaluation metrics included accuracy, precision, and recall, with the model achieving an approximate accuracy of 77%.</li>
    </ul>
  </li>
  <li><b>Findings</b>
    <ul>
      <li>Observed correlations between attributes like parental education and test preparation with academic scores.</li>
      <li>Limited impact of sports participation on performance, as per the hypothesis test results.</li>
    </ul>
  </li>
</ol>


<h2>Results</h2>
<p>
The KNN model achieved an accuracy of 77% but demonstrated a low recall (0.16%), underscoring the model’s limited ability to identify positive cases. The analysis highlighted the influence of parental education and socio-economic factors on student performance.
</p>

<h2>Limitations & Future Directions</h2>
<ul>
  <li><b>Limitations:</b> Sampling biases, missing data, and the lack of additional contextual factors like socio-economic background.</li>
  <li><b>Future Work:</b> Additional data collection to include unexplored variables, examining broader socio-economic impacts, and enhancing predictive performance.</li>
</ul>

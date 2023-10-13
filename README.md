<h1>Customer Segmentation Using Clustering</h1>

<h2>Overview</h2>
<p><strong>Objective:</strong> This case requires developing customer segmentation to give recommendations such as saving plans, loans, wealth management, etc. to target customer groups.</p>

<h2>Data Description</h2>
<p>The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.</p>

<h3>Attribute Information:</h3>
<ul>
  <li><strong>CUSTID:</strong> Identification of Credit Card holder (Categorical)</li>
  <li><strong>BALANCE:</strong> Balance amount left in their account to make purchases</li>
  <li><strong>BALANCEFREQUENCY:</strong> How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)</li>
  <!-- Add more attribute descriptions here -->
</ul>

<h2>Clustering Methods</h2>
<p>We employed various clustering methods to segment the customers, including:</p>
<ul>
  <li><strong>K-means Clustering:</strong> Used K-means clustering with silhouette score for optimal K selection to segment customers.</li>
  <li><strong>Spectral Clustering</strong></li>
  <li><strong>Agglomerative Clustering</strong></li>
  <li><strong>Gaussian Mixture Model-based Clustering</strong></li>
</ul>

<h2>Data Preprocessing</h2>
<p>Before applying clustering methods, we performed the following data preprocessing steps:</p>
<ul>
  <li>Outliers were removed from the dataset to ensure robust clustering.</li>
  <li>Data was scaled to make variables comparable and prevent any one feature from dominating the clustering process.</li>
  <!-- Add more data preprocessing steps here -->
</ul>

<!-- Add more content about the results, findings, and recommendations here if desired -->

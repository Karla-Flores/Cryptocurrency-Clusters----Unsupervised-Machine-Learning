<h1>Cryptocurrency Clusters--Unsupervised Machine Learning</h1>
<hr>
<br>
<h3>Background</h3>
<hr>
<p align= 'justify'>This project aims to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
An investment bank could use this classification report to propose a new cryptocurrency investment portfolio to its clients.
We use the following methods for the analysis:</p>
<br>
<ul>
<li>Preprocessing the database.</li>
<li>Reducing the data dimension using Principal Component Analysis.</li>
<li>Clustering cryptocurrencies using K-Means.</li>
<li>Visualizing classification results with 2D and 3D scatter plots.</li>
</ul>
<h3>Process</h3>
<hr>
<ul>
<li><strong>Preprocessing the database.</strong></li>
<p align= 'justify'>Following the preprocessing instructions and cleaning phase, a total of 532 tradable cryptocurrencies were left. </p>
<li><strong>Reducing Data Dimensions with PCA.</strong></li>
<p align= 'justify'>The PCA algorithm was used for reducing the data after the preprocessing, in this case the components number was 90.</p>

<li><strong>Clustering Cryptocurrencies using K-Means - Elbow Curve</strong></li>
<p align= 'justify'>The purpose of K-means algorithm was to predict the K clusters for the cryptocurrencies.   Also, an elbow curve was produced using the K-Means method iterating on K values from 1 to 10.</p>
<p align= 'center'>
<img src='https://github.com/Karla-Flores/Cryptocurrency-Clusters--Unsupervised-Machine-Learning/blob/main/Screenshots/Elbow_Curve.png'>
</p>
<li><strong>Visualizing classification results with 2D and 3D scatter plots.</strong></li>
<p align= 'justify'></p>
  
<strong><i>2D - Scatter plot with clusters</strong></i><br>
<p align= 'center'><img src = 'https://github.com/Karla-Flores/Cryptocurrency-Clusters--Unsupervised-Machine-Learning/blob/main/Screenshots/Scatterplot.png'></p>
<strong><i>3D - Scatter plot with clusters</strong></i><br>
<img src = 'https://github.com/Karla-Flores/Cryptocurrency-Clusters--Unsupervised-Machine-Learning/blob/main/Screenshots/3D.png'><br>

<h3>Summary </h3>
<hr>
<p align= 'justify'>After the Custer analysis with K-means, the result determined four clusters to be considered tradable cryptocurrencies.</p>


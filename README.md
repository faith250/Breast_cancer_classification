<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Breast Cancer Classification</title>
</head>
<body>

<h1>Breast Cancer Classification</h1>

<p>This project implements a machine learning model to classify breast cancer types using the Wisconsin Breast Cancer dataset. The classification is done using various algorithms from the <code>scikit-learn</code> library, with Logistic Regression giving the best result.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#algorithms-used">Algorithms Used</a></li>
    <li><a href="#model-results">Model Results</a></li>
    <li><a href="#epoch-analysis">Epoch Analysis</a></li>
</ul>

<h2 id="dataset">Dataset</h2>
<p>The dataset used is the <strong>Wisconsin Breast Cancer dataset</strong>, which contains attributes that describe various characteristics of cell nuclei present in breast cancer. Each sample is labeled as either <em>Malignant</em> or <em>Benign</em>.</p>

<h2 id="algorithms-used">Algorithms Used</h2>
<p>The following classification models were applied:</p>
<ol>
    <li><strong>Logistic Regression</strong></li>
    <li><strong>K-Nearest Neighbors</strong></li>
    <li><strong>Support Vector Machine</strong></li>
    <li><strong>Decision Tree</strong></li>
    <li><strong>Random Forest</strong></li>
    <li><strong>Gradient Boosting</strong></li>
    <li><strong>Naive Bayes</strong></li>
    <li><strong>Artificial Neural Network</strong></li>
    <li><strong>Quadratic Discriminant Analysis</strong></li>
</ol>

<h2 id="model-results">Model Results</h2>
<p>Logistic Regression achieved the best accuracy among the models tested. Below is a comparison of the accuracies for each model:</p>
<ul>
    <li>Logistic Regression: <code>97.37%</code></li>
    <li>K-Nearest Neighbors: <code>95.61%</code></li>
    <li>Support Vector Machine: <code>96.49%</code></li>
    <li>Decision Tree: <code>92.98%</code></li>
    <li>Random Forest: <code>96.49%</code></li>
    <li>Gradient Boosting: <code>96.14%</code></li>
    <li>Naive Bayes: <code>93.51%</code></li>
    <li>Artificial Neural Network: <code>94.74%</code></li>
    <li>Quadratic Discriminant Analysis: <code>92.28%</code></li>
</ul>

<h2 id="epoch-analysis">Epoch Analysis</h2>
<p>For Logistic Regression, we analyzed the model's performance over different numbers of epochs. After 10 epochs, the accuracy reached a peak (around <code>97.37%</code>), and beyond this point, the accuracy became stagnant:</p>

<ul>
    <li><strong>10 epochs:</strong> 97.37% accuracy</li>
    <li><strong>50 epochs:</strong> 96.49% accuracy</li>
    <li><strong>100 epochs:</strong> 96.49% accuracy</li>
    <li><strong>200 epochs:</strong> 96.49% accuracy</li>
    <li><strong>500 epochs:</strong> 96.49% accuracy</li>
    <li><strong>1000 epochs:</strong> 96.49% accuracy</li>
</ul>

<p>This shows that after 10 epochs, the model has essentially converged and additional training does not improve performance.</p>

<h2>Conclusion</h2>
<p>This project demonstrates the application of several classification models to predict breast cancer diagnosis. Logistic Regression performs best, with performance stabilizing after 10 epochs. This implementation can serve as a basis for further exploration and optimization in medical data classification tasks.</p>

<h2>References</h2>
<p>For more details on each algorithm and their implementations, please refer to the <a href="https://scikit-learn.org/stable/" target="_blank">scikit-learn documentation</a>.</p>

</body>
</html>

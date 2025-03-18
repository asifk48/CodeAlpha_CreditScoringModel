<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1 align="center">💳 Credit Scoring Model 🔍</h1>
<p align="center">
    <img src="https://img.shields.io/badge/Python-3.9-blue?style=for-the-badge&logo=python">
    <img src="https://img.shields.io/badge/ML-Powered-orange?style=for-the-badge">
    <img src="https://img.shields.io/badge/Scikit--learn-ML-green?style=for-the-badge&logo=scikit-learn">
</p>

<h2 id="project-overview">📖 Project Overview</h2>
<p>
    Credit risk assessment is a crucial process in the financial industry.  
    This project builds a <strong>Credit Scoring Model</strong> to predict loan defaults.  
    By analyzing historical financial data, we applied <strong>Machine Learning</strong> techniques.
</p>

<p>🎯 <strong>Objective:</strong> Develop a robust credit risk model, identify key risk factors, and optimize lending decisions.</p>
<hr>

<h2 id="technologies-used">🛠️ Technologies Used</h2>
<table border="1">
    <tr>
        <th>📌 Category</th>
        <th>🔧 Tools & Technologies</th>
    </tr>
    <tr>
        <td>Programming</td>
        <td>Python 🐍</td>
    </tr>
    <tr>
        <td>Libraries</td>
        <td>Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost</td>
    </tr>
    <tr>
        <td>Tools</td>
        <td>Jupyter Notebook, GridSearchCV</td>
    </tr>
</table>
<hr>

<h2 id="dataset-details">📊 Dataset Details</h2>
<ul>
    <li>📁 <strong>Source:</strong> Kaggle / Open Financial Data</li>
    <li>📌 <strong>Features:</strong> Loan amount, Income, Credit Score, Debt-to-Income ratio, etc.</li>
    <li>⚖️ <strong>Class Distribution:</strong> 80% non-default, 20% default (Balanced with SMOTE)</li>
</ul>
<hr>

<h2 id="key-findings">📈 Key Findings</h2>
<ul>
    <li>🔄 <strong>SMOTE</strong> handled class imbalance, improving fairness.</li>
    <li>📊 Feature selection improved model accuracy significantly.</li>
</ul>

<h2 id="model-performance">⚡ Model Performance</h2>
<table border="1">
    <tr>
        <th>Model</th>
        <th>Accuracy</th>
        <th>Precision</th>
        <th>Recall</th>
        <th>F1-Score</th>
    </tr>
    <tr>
        <td>Logistic Regression</td>
        <td>78%</td>
        <td>72%</td>
        <td>68%</td>
        <td>70%</td>
    </tr>
    <tr>
        <td>Random Forest</td>
        <td>85%</td>
        <td>80%</td>
        <td>75%</td>
        <td>77%</td>
    </tr>
    <tr>
        <td><strong>🚀 XGBoost (Best)</strong></td>
        <td><strong>88%</strong></td>
        <td><strong>84%</strong></td>
        <td><strong>81%</strong></td>
        <td><strong>82%</strong></td>
    </tr>
</table>
<hr>

<h2 id="visualizations">📉 Visualizations</h2>
<ul>
    <li>📊 Feature Importance Graph</li>
    <li>📈 Default vs. Non-Default Customer Distribution</li>
    <li>📉 ROC Curve for Model Comparison</li>
</ul>
<hr>

<h2 id="conclusion">📝 Conclusion</h2>
<p>
    The model successfully identifies high-risk customers.  
    Businesses can use these insights to optimize lending policies and minimize bad debt.
</p>
<hr>

<h2 id="future-scope">🚀 Future Scope</h2>
<ul>
    <li>Deploying the model as an API using Flask/FastAPI.</li>
    <li>Enhancing performance with deep learning.</li>
    <li>Real-time credit risk monitoring.</li>
</ul>
<hr>

<h2 id="how-to-use">📂 How to Use</h2>
<ol>
    <li>Clone this repository:
        <pre><code>git clone https://github.com/asifk48/Credit-Scoring-Model.git</code></pre>
    </li>
    <li>Install dependencies:
        <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li>Run the Jupyter Notebook file:
        <pre><code>jupyter notebook Credit_Scoring_Model.ipynb</code></pre>
    </li>
</ol>
<hr>

<h2 id="contributors">🤝 Contributors</h2>
<ul>
    <li><strong>Mohammad Asif Khan</strong> (<a href="https://github.com/asifk48">GitHub Profile</a>)</li>
</ul>
<hr>

<h2 id="contact">📬 Contact</h2>
<p>
    📧 Email: <a href="mailto:mohammadasif7494@gmail.com">mohammadasif7494@gmail.com</a><br>
    🌐 <a href="https://www.linkedin.com/in/mohammad-asif-khan-a3089a24a">LinkedIn</a>
</p>

</body>
</html>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multicollinearity and PLS Regression: Theory and Applications</title>
</head>

<body>
    <h1>Multicollinearity and PLS Regression: Theory and Applications</h1>
    <h2>Introduction</h2>
    <p>Welcome to the project on Multicollinearity and PLS Regression! In this project, we aim to explore and model data
        exhibiting strong multicollinearity among predictors. The dataset we'll be working with contains information from
        the 2022 French presidential elections, focusing on modeling the results of the second round and identifying
        trends and outliers across different regions.</p>

    <h2>About the Data</h2>
    <p>The dataset comprises 107 observations corresponding to various regions including metropolitan, overseas, and
        French citizens abroad. It includes variables such as the number of registered voters, turnout, abstentions,
        valid votes, blank or null ballots, and votes received by each candidate in both rounds of the elections.</p>

    <h2>Project Tasks</h2>
    <ol>
        <li>Data Exploration:</li>
        <ul>
            <li>Conduct descriptive statistics (univariate and bivariate) to understand the data distribution and
                relationships.</li>
            <li>Utilize scatter plots and correlation mapping to visualize the data.</li>
        </ul>
        <li>Multidimensional Analyses:</li>
        <ul>
            <li>Explore multidimensional analyses for each round individually and combined, justifying the choice of
                methods.</li>
            <li>Apply suitable methods to identify underlying patterns and relationships in the data.</li>
        </ul>
        <li>Univariate Models:</li>
        <ul>
            <li>Estimate univariate models to predict proportions of abstentions, blank/null ballots, and votes for each
                candidate in the second round using predictors from the first round.</li>
            <li>Apply Ordinary Least Squares (OLS) regression and comment on the results, considering multicollinearity.
            </li>
        </ul>
        <li>Multivariate Models:</li>
        <ul>
            <li>Model the second round results based on the first round using multivariate approaches.</li>
            <li>Apply Partial Least Squares (PLS) Regression and Principal Component Regression (PCR) using
                Scikit-learn.</li>
            <li>Compare and interpret the results obtained from different methods.</li>
        </ul>
    </ol>

    <h2>Tools Used</h2>
    <p>Python Libraries: We primarily used scikit-learn for implementing PLS Regression and PCR, pandas for data
        manipulation, and matplotlib for data visualization.</p>
    <p>Statistical Techniques: We employed various statistical techniques to explore relationships between variables,
        handle multicollinearity, and model the data effectively.</p>

    <h2>Conclusion</h2>
    <p>This project provides valuable insights into handling multicollinearity and utilizing Partial Least Squares
        Regression in predictive modeling. By applying these techniques to real-world data from the 2022 French
        presidential elections, we gain a deeper understanding of the underlying patterns and trends in the electoral
        process.</p>
</body>

</html>

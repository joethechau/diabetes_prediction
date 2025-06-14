# PCA and Logistic Regression for Diabetes Prediction – R

<p><strong>Used PCA and logistic regression to analyze factors influencing diabetes status in 768 patients.</strong></p>
<ul>
  <li>Variables included glucose, insulin, BMI, age, pregnancies, etc. from <code>diabetesdata.csv</code>.</li>
  <li><strong>PCA:</strong> Standardized 8 predictors → 3 PCs retained (explaining >60% variance).</li>
  <li><strong>PC1:</strong> “Risk Factor” (high BMI, glucose, insulin); <strong>PC2:</strong> “Demographic vs. Metabolic Contrast” (age & pregnancies vs. BMI & insulin).</li>
  <li>Visualized PCA results using biplot; clusters in PC1 direction indicated higher diabetes risk.</li>
  <li><strong>Logistic Regression:</strong> Fit model with PC1–PC3; all statistically significant (p &lt; 0.05).</li>
  <li><strong>Stepwise Selection:</strong>
    <ul>
      <li><em>Backward:</em> Selected glucose, BMI, pregnancies, diabetesPF, bloodpressure, age, insulin.</li>
      <li><em>Forward:</em> Selected same set, excluding skin thickness.</li>
    </ul>
  </li>
</ul>



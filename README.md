ata & Feature Insights
1️⃣ Strongest survival factor
Females had a much higher survival rate than males.
This confirms the historical “women first” evacuation policy.
In most models, sex becomes one of the top predictive features.
👉 Insight: Gender alone provides strong predictive power for survival.

2️⃣ Passenger class strongly influenced survival
1st class passengers survived significantly more than 2nd and 3rd class.
3rd class had the lowest survival rate.
👉 Insight: Socio-economic status (represented by pclass) played a critical role in survival chances.

3️⃣ Fare is positively correlated with survival
Higher fare → higher survival probability.
Fare indirectly captures class, cabin proximity, and access to lifeboats.
👉 Insight: Fare acts as a proxy feature for privilege and safety access.

4️⃣ Age had a moderate but meaningful impact
Children had better survival rates.
Elderly passengers had lower survival probabilities.
Mean imputation for missing ages worked reasonably well but reduced variance.
👉 Insight: Age is useful, but non-linear effects (child vs adult vs elderly) matter more than raw age.

🧹 Data Cleaning Insights
5️⃣ Dropping high-missing columns improved model stability
Removed Columns: deck, embark_town, alive, who, etc.
👉 Insight: Removing columns with excessive missing or redundant information helped prevent noise and overfitting.

6️⃣ Encoding categorical features was essential
Variables like sex and embarked needed encoding.
Models would fail or underperform without this step.
👉 Insight: Proper preprocessing directly affects model performance.

🤖 Model Performance Insights
7️⃣ Logistic Regression performed surprisingly well
Delivered strong baseline accuracy
Interpretable coefficients helped understand feature impact
👉 Insight: For structured/tabular data, simple linear models can compete with complex ones.

8️⃣ KNN performance depended heavily on scaling
Accuracy improved only after feature scaling
Sensitive to k value and feature magnitude
👉 Insight: Distance-based models require normalization to perform well.



Performed well on training data

Lower generalization without depth control

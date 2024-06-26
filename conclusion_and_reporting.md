# Conclusion and Report

## Summary of Findings
1. **Age vs. Charges**: Medical charges tend to increase with age. Older individuals generally incur higher medical expenses compared to younger individuals.

2. **Sex vs. Charges**: There is no significant difference in medical charges between males and females. Both genders have a similar distribution of charges.

3. **BMI vs. Charges**: Individuals with higher BMI tend to have higher medical charges. This correlation is more pronounced in smokers.

4. **Children vs. Charges**: The number of children does not significantly affect medical charges. Families with different numbers of children show similar charge distributions.

5. **Smoker vs. Charges**: Smokers have significantly higher medical charges compared to non-smokers. This is one of the most impactful factors on medical costs.

6. **Region vs. Charges**: Medical charges vary across different regions. The southeast region tends to have higher medical charges on average.

7. **Interaction Effects**: The interaction between age, sex, and smoking status reveals that older smokers have disproportionately higher medical charges.

## Predictive Modeling
Three regression models were built to predict medical charges:

1. **Linear Regression**:
   - Mean Squared Error (MSE): 35533622.59
   - Mean Absolute Error (MAE): 4190.49

2. **Random Forest Regressor**:
   - Mean Squared Error (MSE): 19247294.57
   - Mean Absolute Error (MAE): 2713.62

3. **Gradient Boosting Regressor**:
   - Mean Squared Error (MSE): 16948558.21
   - Mean Absolute Error (MAE): 2356.27

Among these models, the Gradient Boosting Regressor performed the best, showing the lowest MSE and MAE. This indicates that Gradient Boosting is more effective in predicting medical charges accurately.

## Recommendations

1. **Health Interventions**: Targeted health interventions for smokers could significantly reduce medical costs. Smoking cessation programs and preventive healthcare measures can be beneficial.

2. **Obesity Programs**: Implementing programs to address obesity and promoting healthy lifestyles could help in reducing medical charges, especially among individuals with high BMI.

3. **Regional Policies**: Policymakers should consider regional disparities in medical charges and adjust healthcare policies to ensure equitable healthcare access and cost management across all regions.

4. **Preventive Care**: Emphasizing preventive care for older adults can help in mitigating the rise in medical charges with age. Regular health check-ups and early interventions can be effective strategies.
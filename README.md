Introduction:
Diabetes is a chronic metabolic condition characterized by high blood sugar levels, elevated triglycerides, and disruptions in normal metabolic processes. This analysis aims to examine the factors that may influence blood sugar levels, including age, blood pressure, diet type, medication use, triglyceride levels, number of pregnancies, waist and hip circumference, hypertension, family history, waist-to-hip ratio, HbA1c, low-density lipoprotein (LDL), high-density lipoprotein (HDL), and overall health outcome.
Story of the Data:
The dataset used for this analysis was obtained from Kaggle.com, a public online data repository. It is organized in a tabular format consisting of rows and columns, with variables such as age, blood pressure, diet type, medication use, triglyceride levels, pregnancies, waist circumference, hip circumference, hypertension status, family history, among others. These variables represent known risk factors for diabetes, as they directly or indirectly contribute to the development of the condition over time. The dataset provides insights into the relationships between these factors and diabetes outcomes.
Sugar and diabetic status of people across different age groups
Effect of medication use on blood sugar level
The relationship between LDL, HDL and triglyceride levels in the body
Family history and diabetes
Limitations were the fact that no year or date of data collection, no status report of whether the individual had, or previously had diabetes or elevated sugar levels.
Data splitting and preprocessing:
Data cleaning: The dataset was cleaned upon download from Kaggle, I checked consistency, duplicates, missing values, blanks row & columns.
Data Transformations: To enable swift analytical process, the dataset was transformed from normal excel table into a standard excel table, this enables proper colour usage on the table and also automate the table.
Data splitting: the dataset was splatted into dependent and independent data category based on their ability to have a separate existence.
 Independent  Values: Age, Blood pressure, dietscore, tryglyceride level, waist to hip ratio,, hypertension family history, diabetes family history
Dependent Values: Hba1c, Low  Density Lipoprotein(LDL), High Density Lipoprotein(HDL), Diagnose -diabetes

Industry context: Healthcare and wellness.
Industry stakeholders: Pharmacist, Pharmaceutical companies, Governments, Physicians, Healthcare Practitioner’s, and Individuals.
 
Value to the Industry: Reducing incidence of high blood sugar level leading reduced diabetes and keeping diabetic patient stable while reduce crisis and complication.
Potential Analysis/Questions
Potential Analysis/ Questions
1. what are the most susceptible age to diabetes?
2. what is hypertension effect on blood sugar level
3. HbA1c by age
4. Blood sugar level in relation to HbA1c
5. what are the susceptible ages to high blood sugar level?
6. who are those with high cholesterols?
7. Family history and blood sugar level?
8. what is the Implication of high BMI?
9. What diet means to diabetes persons

In-Analysis
                                        IN-ANALYSIS OBSERVATIONS
 Average Fasting Glucose by Age Group
The chart shows a progressive increase in average fasting glucose levels as age increases.
Individuals aged 18–32 recorded the lowest average fasting glucose level (≈106 mg/dL).
The 33–47 age group shows a moderate increase to about 109 mg/dL, indicating a gradual rise in glucose levels with age.
The 48–62 and 63–77 groups continue this upward trend with averages of approximately 112 mg/dL and 115 mg/dL respectively.
The 78–92 age group recorded the highest average fasting glucose level (≈118 mg/dL) among all groups.
Average Fasting Glucose by HDL Cholesterol Levels
The chart illustrates the relationship between HDL cholesterol levels and average fasting glucose levels.
Individuals with lower HDL levels (20–29) recorded the highest average fasting glucose level (≈115 mg/dL).
As HDL levels increase, the average fasting glucose level gradually decreases.
For example, individuals within the 40–49 and 50–59 HDL ranges show moderate glucose levels of approximately 112 mg/dL and 111 mg/dL respectively.
Those with higher HDL levels (80–89 and 90–99) recorded lower average fasting glucose levels (≈109–108 mg/dL).
Average Triglyceride Levels by Age Group
There is  a steady increase in average triglyceride levels as age increases.
Individuals aged 18–32 recorded the lowest average triglyceride level (≈118 mg/dL) among all age groups.
The 33–47 age group shows a noticeable increase to approximately 121 mg/dL, indicating a gradual rise in triglyceride levels with age.
The 48–62 and 63–77 groups continue this upward trend with average levels of about 122 mg/dL and 124 mg/dL respectively.
The 78–92 age group recorded the highest average triglyceride level (≈125 mg/dL).
Glucose Fasting vs Family History of Diabetes
The pie chart illustrates the average fasting glucose levels categorized by family history of diabetes (0 = No, 1 = Yes). The distribution shows that individuals with a family history of diabetes (1) account for a slightly larger proportion of the total average fasting glucose values compared to those without a family history (0).
This suggests a potential association between family history of diabetes and higher fasting glucose levels, indicating that individuals with a diabetic family background may have elevated fasting glucose on average. Although the difference is not extremely large, the visual trend supports the hypothesis that genetic or familial factors could influence glucose regulation.
Body Mass Index (BMI) vs Blood Glucose Level
Positive Relationship Between BMI and Blood Glucose
The chart shows a gradual increase in blood glucose levels as BMI category increases. Individuals in the higher BMI groups tend to have higher average blood glucose levels.
Lowest BMI Group Shows Lowest Glucose Level
The 15–20 BMI category has the lowest mean blood glucose level (106.83), indicating comparatively better glucose regulation among individuals with lower BMI.
Steady Increment Across Categories
Blood glucose increases progressively across BMI groups:
15–20 → 106.83
20–25 → 109.67
25–30 → 111.94
30–35 → 114.59
35–40 → 116.51
This pattern suggests a consistent upward trend rather than abrupt changes.
Highest BMI Category Shows Highest Glucose Level
The 35–40 BMI group records the highest blood glucose level (116.51), indicating a possible association between higher body mass and elevated blood sugar levels the trend is consistent, which may indicate a gradual metabolic impact of increasing BMI on glucose level
 Waist-to-Hip Ratio vs Fasting Blood Glucose
Positive Association Between Waist-to-Hip Ratio and Fasting Glucose
The chart indicates a progressive increase in average fasting blood glucose levels as the waist-to-hip ratio increases, suggesting that individuals with higher central body fat tend to have higher glucose levels.
Lowest Ratio Shows Lowest Glucose Level
The 0.67–0.75 waist-to-hip ratio group records the lowest average fasting glucose (≈106), indicating comparatively better metabolic status among individuals with lower abdominal fat distribution.
Gradual Increase Across Categories
Average fasting glucose increases consistently across ratio groups:
0.67–0.75 → ~106
0.75–0.83 → ~109
0.83–0.91 → ~111
0.91–0.99 → ~113–114
0.99–1.07 → ~115
This pattern demonstrates a steady upward trend rather than sharp fluctuations.
Highest Ratio Group Shows Highest Glucose Level
Individuals in the 0.99–1.07 waist-to-hip ratio category have the highest average fasting glucose (~115), indicating a stronger association between abdominal obesity and elevated glucose levels.
Consistent Increment Pattern
The increase in glucose levels between categories is relatively moderate but consistent, typically rising by 2–3 units per category, which suggests a systematic relationship between fat distribution and glucose metabolism.
Health Implication
The observed trend supports evidence that higher waist-to-hip ratios (greater central obesity) are linked with increased risk of impaired glucose regulation and metabolic disorders, 
Total Cholesterol vs Average Fasting Blood Glucose
Higher Cholesterol Levels Are Associated With Higher Fasting Glucose
The analysis shows that fasting blood glucose tends to increase as total cholesterol levels rise, particularly in the higher cholesterol categories.
Highest Glucose Level in the Highest Cholesterol Group
The 300–324 cholesterol range records the highest average fasting glucose level (117.00), suggesting that individuals with very high cholesterol levels tend to have elevated blood glucose.
Gradual Decline Toward Lower Cholesterol Categories
As cholesterol categories decrease, the average fasting glucose level generally declines:
275–299 → 115.13
250–274 → 114.22
225–249 → 112.77
200–224 → 112.12
175–199 → 111.16
150–174 → 110.24
125–149 → 109.32
100–124 → 108.36
Lowest Cholesterol Group Shows the Lowest Glucose Level
The 100–124 cholesterol category has the lowest average fasting glucose level (108.36), indicating better metabolic balance in individuals with lower cholesterol levels.
Consistent Downward Trend
There is a steady downward pattern in fasting glucose as cholesterol levels decrease, indicating a positive relationship between total cholesterol and blood glucose levels.
Possible Metabolic Link
The trend suggests that higher cholesterol levels may be associated with impaired glucose metabolism, which is commonly observed in metabolic conditions such as metabolic syndrome and type 2 diabetes.
   Analytical Dashboard 
   
   <img width="1769" height="778" alt="Analytical dashboard" src="https://github.com/user-attachments/assets/6da92ff0-550b-4cd9-b907-0b270f89f2d0" />


                    
                      IN-ANALYSIS INSIGHTS/RECOMMENDATION
In-Analysis Insights and Recommendations
1. Age-Related Metabolic Risk
The analysis shows a consistent increase in both fasting glucose and triglyceride levels with age, indicating that metabolic risk tends to rise in older populations. Individuals aged 63–92 exhibit the highest average levels, suggesting that age may be a significant factor influencing glucose regulation and lipid metabolism.
Preventive health monitoring programs should prioritize middle-aged and older adults, encouraging routine glucose and lipid screening to enable early detection of metabolic disorders such as prediabetes or type 2 diabetes.
2. Protective Role of HDL Cholesterol
The results reveal an inverse relationship between HDL cholesterol and fasting glucose levels. Individuals with higher HDL levels tend to have lower average glucose levels, suggesting that HDL may play a protective role in metabolic health.

Lifestyle interventions aimed at increasing HDL levels—such as regular physical activity, healthy dietary patterns, and reduced saturated fat intake—may help improve glucose metabolism and reduce metabolic disease risk.
3. Genetic Influence on Glucose Regulation
The analysis indicates that individuals with a family history of diabetes show slightly higher average fasting glucose levels compared to those without such history. Although the difference is moderate, the pattern suggests a possible hereditary influence on glucose regulation.
Individuals with a family history of diabetes should be considered a higher-risk group and may benefit from earlier screening, targeted lifestyle interventions, and awareness programs focused on diabetes prevention.
4. Impact of Body Mass Index on Blood Glucose
The data shows a steady increase in blood glucose levels across increasing BMI categories, indicating a clear positive association between body weight and glucose levels. Individuals in the highest BMI category (35–40) recorded the highest average glucose levels.
Weight management strategies such as balanced nutrition, increased physical activity, and lifestyle modification programs should be emphasized to reduce obesity-related metabolic risks.
5. Central Obesity as a Strong Metabolic Indicator
The analysis demonstrates a consistent rise in fasting glucose as waist-to-hip ratio increases, suggesting that central fat distribution may be a stronger predictor of impaired glucose regulation than overall body weight alone.
Health assessments should include waist-to-hip ratio measurements alongside BMI, as abdominal obesity appears to be closely associated with elevated glucose levels and metabolic risk.
6. Cholesterol and Glucose Metabolic Link
The results indicate a positive relationship between total cholesterol levels and fasting blood glucose, with the highest cholesterol group showing the highest glucose levels. This pattern suggests a possible interaction between lipid metabolism and glucose regulation, commonly observed in metabolic syndrome.
Integrated health strategies should focus on managing both cholesterol and glucose levels simultaneously, as controlling lipid levels may also contribute to improved metabolic health outcomes.
7. Evidence of Metabolic Syndrome Patterns
Across multiple variables—BMI, waist-to-hip ratio, cholesterol, triglycerides, and HDL—there is a consistent pattern linking higher cardiovascular risk factors with elevated fasting glucose levels. This combination of trends aligns with characteristics commonly associated with metabolic syndrome.
Future analyses could explore multivariate relationships or predictive modeling to determine which factors (e.g., BMI, HDL, cholesterol) are the strongest predictors of elevated glucose levels.

                                       POST- ANALYSIS OBSERVATIONS
The BMI slicer categorizes individuals into body mass index ranges (15–20, 20–25, 25–30, 30–35, 35–40, allowing the dataset to be analyzed based on different body weight classifications. This segmentation provides a clearer understanding of how body weight influences metabolic health indicators, including fasting glucose, cholesterol levels, triglycerides, waist-to-hip ratio, and family history of diabetes.
1. BMI and Blood Glucose Regulation
Using the BMI slicer reveals a progressive increase in fasting blood glucose levels as BMI categories rise. Individuals within the lower BMI ranges (15–20) generally display lower glucose levels, suggesting healthier metabolic regulation. In contrast, individuals in higher BMI categories (30–40 and above) tend to show elevated glucose levels.
This trend indicates that excess body weight is closely associated with impaired glucose metabolism, potentially increasing the risk of developing insulin resistance or type 2 diabetes.
2. BMI and Cholesterol Levels
When analyzing cholesterol levels across BMI groups, higher BMI categories often correspond with elevated total cholesterol levels. Individuals in overweight and obese ranges may experience changes in lipid metabolism, leading to increased cholesterol accumulation.
This interaction suggests that higher BMI may contribute to both glucose imbalance and lipid abnormalities, which together increase cardiovascular and metabolic disease risk.
3. BMI and Triglyceride Levels
Triglyceride levels are also influenced by BMI. Individuals in higher BMI categories tend to show increased triglyceride levels, which is commonly associated with metabolic syndrome and insulin resistance.
The BMI slicer allows analysts to observe how triglyceride levels change across weight groups, revealing that overweight and obese individuals are more likely to exhibit elevated triglyceride concentrations compared to those with normal BMI.
4. BMI and Waist-to-Hip Ratio
BMI often correlates with waist-to-hip ratio, another important indicator of fat distribution. Individuals in higher BMI categories typically display higher waist-to-hip ratios, indicating greater abdominal or central fat accumulation.
Central obesity is particularly important because it is strongly linked to higher fasting glucose levels and increased metabolic risk, meaning BMI and fat distribution together provide stronger insight into overall metabolic health.
5. BMI and Family History of Diabetes
When the BMI slicer is used together with the family history of diabetes filter, it becomes possible to identify individuals who may have both genetic and lifestyle-related risk factors. For example, individuals with higher BMI and a family history of diabetes may exhibit stronger patterns of elevated glucose levels and other metabolic indicators.
This combined analysis highlights how genetic predisposition and body weight can interact to influence diabetes risk.
The Family History of Diabetes slicer (0 = No, 1 = Yes) enables a segmented analysis that helps determine how genetic predisposition interacts with other metabolic risk factors such as BMI, cholesterol levels, triglycerides, and waist-to-hip ratio. By filtering the dataset through this variable, it becomes possible to observe whether individuals with a hereditary risk exhibit stronger metabolic patterns associated with elevated fasting glucose.
1. Interaction Between Family History and BMI
When the data is segmented using the family history slicer, individuals with a family history of diabetes and higher BMI levels tend to show relatively higher fasting glucose values. Since BMI is already positively associated with glucose levels, the presence of a genetic predisposition may amplify the metabolic impact of excess body weight.
This suggests that individuals who are both overweight and genetically predisposed may be at a heightened risk of impaired glucose regulation.
2. Relationship With Cholesterol Levels
The earlier analysis showed that higher total cholesterol levels correspond with increased fasting glucose levels. When filtered by family history, this relationship becomes particularly important because individuals with hereditary risk and elevated cholesterol levels may experience compounded metabolic stress.
This reinforces the idea that lipid metabolism and glucose metabolism are interconnected, particularly for individuals with genetic susceptibility to diabetes.
3. Association With Triglyceride Levels
Triglyceride levels were observed to increase gradually across age groups and are commonly linked to metabolic disorders. When examining individuals with a family history of diabetes, elevated triglyceride levels may indicate a higher likelihood of developing insulin resistance or metabolic syndrome.
This relationship highlights how genetic predisposition combined with abnormal lipid profiles may contribute to worsening metabolic health outcomes.
4. Influence of Waist-to-Hip Ratio
The waist-to-hip ratio analysis demonstrated that higher ratios correspond with increased fasting glucose levels, indicating the role of central obesity in glucose regulation. When combined with the family history filter, individuals with higher waist-to-hip ratios and a diabetic family background may exhibit stronger indicators of metabolic risk.
Central obesity is widely recognized as a key factor in insulin resistance, and its interaction with genetic predisposition may significantly increase vulnerability to metabolic disorders.
                                       POST- ANALYSIS INSIGHTS/RECOMMENDATION
1. Body Weight as a Key Driver of Metabolic Risk
The post-analysis confirms that BMI plays a significant role in influencing metabolic health indicators. Individuals in higher BMI categories consistently show higher fasting blood glucose, cholesterol, and triglyceride levels, indicating a strong association between increased body weight and metabolic imbalance. Additionally, higher BMI groups tend to exhibit greater waist-to-hip ratios, suggesting increased abdominal fat accumulation.
Health monitoring programs should emphasize weight management strategies, including balanced nutrition, regular physical activity:, and lifestyle interventions. Maintaining BMI within a healthy range may significantly reduce the risk of glucose dysregulation and related metabolic disorders.
2. Combined Impact of BMI and Lipid Profiles
The analysis reveals that BMI and lipid indicators (cholesterol and triglycerides) interact closely, with higher BMI categories showing elevated lipid levels. This pattern suggests that individuals with higher body weight may experience simultaneous disruptions in both glucose metabolism and lipid metabolism, increasing the likelihood of cardiovascular complications.
Preventive health strategies should focus on integrated metabolic monitoring, where glucose levels, cholesterol, and triglycerides are assessed together rather than independently. This approach can help identify individuals at risk of developing metabolic syndrome or cardiovascular disease.
3. Central Obesity as a Critical Metabolic Indicator
The findings highlight that waist-to-hip ratio increases alongside BMI and fasting glucose levels, indicating that fat distribution—particularly abdominal fat—plays a critical role in metabolic health. Central obesity appears to strengthen the association between body weight and impaired glucose regulation.
Health assessments should incorporate waist-to-hip ratio measurements alongside BMI to provide a more accurate representation of metabolic risk. This combined measure can help detect individuals who may appear within a normal BMI range but still have elevated risk due to abdominal fat accumulation.
4. Genetic Predisposition and Lifestyle Risk Interaction
The family history of diabetes analysis indicates that individuals with both genetic predisposition and higher BMI tend to demonstrate stronger patterns of elevated fasting glucose and abnormal lipid levels. This suggests that genetic susceptibility may amplify the metabolic effects of lifestyle-related risk factors such as obesity and poor lipid profiles.
Individuals with a family history of diabetes should be prioritized for early screening and preventive interventions, particularly when additional risk factors such as high BMI, elevated cholesterol, or high triglycerides are present.
5. Compounding Effect of Multiple Metabolic Risk Factors
The combined analysis of BMI, cholesterol levels, triglycerides, waist-to-hip ratio, and family history reveals a pattern where multiple metabolic indicators tend to increase simultaneously. This clustering of risk factors resembles patterns commonly associated with metabolic syndrome, where obesity, abnormal lipid levels, and impaired glucose regulation occur together.
Future analytical work should incorporate multivariate analysis, predictive modeling, or risk scoring techniques to identify which combination of variables most strongly predicts elevated fasting glucose or diabetes risk. This would allow for more accurate risk stratification and targeted health interventions.
              
         CONCLUSION
The post-analysis highlights clear relationships between BMI, waist-to-hip ratio, cholesterol levels, triglycerides, and fasting blood glucose, indicating that metabolic health is influenced by multiple interconnected factors. Individuals with higher BMI and greater central fat distribution tend to show elevated glucose levels and unfavorable lipid profiles, suggesting an increased risk of metabolic disorders. The analysis also shows that cholesterol and triglyceride levels rise alongside BMI, reinforcing the link between body weight and lipid metabolism.
Additionally, the family history of diabetes filter reveals that genetic predisposition may amplify the impact of lifestyle-related risk factors such as obesity and abnormal lipid levels. Individuals with both higher BMI and a family history of diabetes demonstrate stronger indicators of metabolic imbalance.
Overall, my findings suggest patterns associated with metabolic syndrome, where multiple risk factors occur simultaneously. These insights highlight the importance of integrated monitoring of body weight, fat distribution, lipid levels, and genetic risk to support early detection and preventive health strategies.





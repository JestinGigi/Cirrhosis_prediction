# Cirhosis Prediction
Cirrhosis is a late stage of scarring (fibrosis) of the liver caused by many forms of liver diseases and conditions, such as hepatitis and chronic alcoholism. 
## Table of Content
- [Dataset](https://www.kaggle.com/datasets/fedesoriano/cirrhosis-prediction-dataset)
- [Attributes](#attributes)
- [Exploratory Analysis](#exploratory-analysis)

## Attributes
1. ID: unique identifier.
2. N_Days: number of days between registration and the earlier of death, transplantation, or study analysis time in July 1986.
3. Status: status of the patient C (censored), CL (censored due to liver tx), or D (death).
4. Drug: type of drug D-penicillamine or placebo.
5. Age: age in [days].
6. Sex: M (male) or F (female).
7. Ascites: presence of ascites N (No) or Y (Yes).
8. Hepatomegaly: presence of hepatomegaly N (No) or Y (Yes).
9. Spiders: presence of spiders N (No) or Y (Yes).
10. Edema: presence of edema N (no edema and no diuretic therapy for edema), S (edema present without diuretics, or edema resolved by diuretics), or Y (edema despite diuretic therapy).
11. Bilirubin: serum bilirubin in [mg/dl].
12. Cholesterol: serum cholesterol in [mg/dl].
13. Albumin: albumin in [gm/dl].
14. Copper: urine copper in [ug/day].
15. Alk_Phos: alkaline phosphatase in [U/liter].
16. SGOT: SGOT in [U/ml].
17. Triglycerides: triglycerides in [mg/dl].
18. Platelets: platelets per cubic [ml/1000].
19. Prothrombin: prothrombin time in seconds [s].
20. Stage: histologic stage of disease (1, 2, 3, or 4).

## Exploratory Analysis
### Stage Vs No. Of Patients
- The below graph shows patients registered with a given severity, out of which patients at stage 3 are more prominent.
<p align=center><img width="350" alt="image" src="https://github.com/JestinGigi/Cirrhosis_prediction/assets/75965382/19ba4615-7439-46ca-9f9a-5f75f2a9d799"></p>

### Age/Gender Dependency on Severity
- The above visualization provides insights into the dependence of cirrhosis severity on an individual's gender. Based on the graph and recent studies, it is observed that males are more prone to cirrhosis. This may indicate poor lifestyle choices(excessive alcoholism), unhealthy eating habits, and compromised physical/mental health.
- Cirrhosis is a condition characterized by the scarring of the liver, leading to liver dysfunction. As individuals age, their liver function naturally declines, as depicted in the visualizations below.
<p align=center><img width="347" alt="image" src="https://github.com/JestinGigi/Cirrhosis_prediction/assets/75965382/724732ba-38a7-412c-87be-273c03f6a11a"></p>

### Symptoms at various stages
- Ascites: Ascites refers to the accumulation of fluid in the abdominal cavity.
- Hepatomegaly: Hepatomegaly refers to the enlargement of the liver
- Spiders: These are dilated blood vessels on the skin's surface that resemble spider legs.
- Edema: Edema refers to the swelling caused by the accumulation of fluid in tissues
  <p align="center"><img width="350" alt="image" src="https://github.com/JestinGigi/Cirrhosis_prediction/assets/75965382/44504e35-235e-4d3b-b33c-da651c633929"></p>

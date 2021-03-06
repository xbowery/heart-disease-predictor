# Heart Disease Predictor

Heart disease and stroke will become a leading cause of both death and disability worldwide, with the number of fatalities projected to increase to over 20 million a year and by 2030 to over 24 million a year. Many studies has found that heart disease has a correlation to factors such as age, sex, blood pressure, exercise protocol, etc. With a rich dataset provided in Cleveland, Veterans Administration (VA) Long Beach, Hungary and Switzerland, our team was inspired to predict the top indicators of heart disease so as to better educate the general public.

(Done as part of Hackwagon's DS102 Project Requirement)

# I. Problem Statement / Research Topic

Heart disease and stroke will become a leading cause of both death and disability worldwide, with the number of fatalities projected to increase to over 20 million a year and by 2030 to over 24 million a year. Many studies has found that heart disease has a correlation to factors such as age, sex, blood pressure, exercise protocol, etc. With a rich dataset provided in Cleveland, Veterans Administration (VA) Long Beach, Hungary and Switzerland, our team was inspired to predict the top indicators of heart disease so as to better educate the general public. 

This study will explore the following questions:

- Which risk attribute correlates most closely with heart disease?
- Can we compare on a Multivariate analysis of multiple factors to see if a mixture of risk factors will increase the probability of getting heart disease?
- Can we use Machine Learning Techniques (Multivariate Analysis, Logistic Regression, Decision Tree) to help us predict heart disease?


<hr class="solid">
<h3>Glossary</h3>

<b>Fasting blood sugar</b>: 
A blood sample will be taken after an overnight fast. A fasting blood sugar level less than 100 mg/dL (5.6 mmol/L) is normal. A fasting blood sugar level from 100 to 125 mg/dL (5.6 to 6.9 mmol/L) is considered prediabetes. If it's 126 mg/dL (7 mmol/L) or higher on two separate tests, you have diabetes.

<b>METs Achieved</b>:
Metabolic Equivalent - A MET is a ratio of your working metabolic rate relative to your resting metabolic rate.

<b>Thal:</b>
Thalassemia (thal-uh-SEE-me-uh) is an inherited blood disorder that causes your body to have less haemoglobin than normal. Haemoglobin enables red blood cells to carry oxygen. Thalassemia can cause anemia, leaving you fatigued. If you have mild thalassemia, you might not need treatment.

<b>Exercise Induced Angina:</b>
Angina is a type of chest pain that results from reduced blood flow to the heart. A lack of blood flow means your heart muscle isn't getting enough oxygen. The pain is often triggered by physical activity or emotional stress. Stable angina, also called angina pectoris, is the most common type of angina. When one experiences chest pain that doesn't meet the criteria for angina, it's known as atypical chest pain. Non-angina pain describes chest pain that resembles heart pain in patients who do not have heart disease.

<b>Resting electrocardiographic results:</b>
The resting electrocardiogram is a test that measures the electrical activity of the heart. The heart is a muscular organ which pumps blood through rhythmic contractions induced by electric impulses generated by the sinus node, the heart???s natural pacemaker. 

<b>ST depression:</b>
ST depression induced by exercise relative to rest. ST depression refers to a finding on an electrocardiogram, wherein the trace in the ST segment is abnormally low below the baseline.

<table>
    <tr>
    <td><img src="https://litfl.com/wp-content/uploads/2018/10/ST-segment-depression-upsloping-downsloping-horizontal.png" alt="ST-segment-depression" style="width:100%"></td><td><img src="https://th.bing.com/th/id/Rf8c775e7f28d1a43a07bb0320d94ea2b?rik=5sUcQU6RjLs5fA&riu=http%3a%2f%2fwww.cvphysiology.com%2fuploads%2fimages%2fCAD012+ECG+ST+depression.png&ehk=x7m5WB3JAr9TLSFEINAMoJzvq%2fYi7AytUFSfmxGUJAs%3d&risl=&pid=ImgRaw" alt="ST-depression" style="width:100%"></td>
    </tr>
</table>
    


<b>Slope peak exercise:</b>
Slope of peak exercise ST segment (image above)
1: upslope, 2: flat,    3: downslope

<b>No. of major vessels colored (by flouroscopy):</b>
Fluoroscopy is a test that uses a steady beam of x-rays to look at parts of the body and movement within the body, such as blood moving through a blood vessel. A dye (contrast material) that shows up on fluoroscopy can be put in a vein (IV) or swallowed so vessels or organs show up clearly.
No. of major vessels colored by flouroscopy: 0-3 out of 4

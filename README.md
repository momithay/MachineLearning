# Dataset Description 

The provided data is a modified version of a publicly available data source, and is subject to copyright.

### Donor of database: 
                          The Johns Hopkins University
                          Johns Hopkins Road
                          Laurel, MD 20707
                          (301) 953-6231

### Licence agreement: 

The dataset can only be used for the purpose of this assignment. Sharing or distributing this data or using this data for any other commercial or non-commercial purposes is prohibited.

### Project Objective:
For an ICU, the ability to predict if a patient in ICU will develop a sepsis is very beneficial. That would assist with reducing the risk of health complications, and managing the ICU resources (such as bed availability, etc.). In this assignment, we develop a ML model to predict if a patient will develop sepsis in the period of their stay in the ICU, based on provided attributes (features) related to: patient characteristics, diagnoses, treatments, services, hospital charges and patients socio-economic background.

The machine learning task we are interested in is: “Predict if a given in ICU would not develop a sepsis (Sepsis Negative / class 0) or will develop sepsis (Sepsis Positive / class 1) during their ICU stay”.

### Data Fields

| Column Name | Attribute/Target| Description|
|-------|-------|------ |
| ID  | N/A   |Unique number to represent patient ID |                                                                                                
| PRG   | Attribute1       |  Plasma glucose |
| PL| Attribute 2     |   Blood Work Result-1 (mu U/ml) |                                                                                  |
| PR | Attribute 3      | Blood Pressure (mm Hg)    
| SK | Attribute 4      | Blood Work Result-2 (mm) |
| TS             | Attribute 5      |     Blood Work Result-3 (mu U/ml)|                                                                                   | M11    | Attribute 6    |  Body mass index (weight in kg/(height in m)^2|
| BD2             | Attribute 7     |   Blood Work Result-4 (mu U/ml)|                                                                         |
| Age    | Attribute 8      |    patients age  (years)   |
| Insurance | N/A     | If a patient holds a valid insurance card|
| Sepssis        | Target           | Positive: if a patient in ICU will develop a sepsis , and Negative: otherwise |

###### Missing Attribute Values: Yes

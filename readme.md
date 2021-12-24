# (Finding Donors for Charity ML - Supervised Learning Project)
## by (Moheb Maher)

## Dataset:
> - The dataset for this project originates from the UCI Machine Learning Repository. The datset was donated by Ron Kohavi and Barry Becker, after being published in the article "Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid". You can find the article by Ron Kohavi online. The data investigated here consists of small changes to the original dataset, such as removing the 'fnlwgt' feature and records with missing or ill-formatted entries.
> - Featureset Exploration
>> * age: continuous.
>> * workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
>> * education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, >> * >> >> * Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
>> * education-num: continuous.
>> * marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
>> * occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
>> * relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
>> * race: Black, White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other.
>> * sex: Female, Male.
>> * capital-gain: continuous.
>> * capital-loss: continuous.
>> * hours-per-week: continuous.
>> * native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

## Objectives:
> - Several supervised algorithms were applied to accurately model individuals' income using data collected from the 1994 U.S. Census.
> - The best candidate algorithm was choosen from preliminary results with further optimization to best model the data. > - The goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000.
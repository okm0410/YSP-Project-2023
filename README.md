# YSP-Project-2023

Research Question:
Can we predict whether someone is at risk of developing lung cancer by analyzing multiple epigenetic factors? 

Expected Coding Work:
Our project will have two parts. The first portion will involve analyzing data from patients diagnosed with lung cancer such as whether the patient regularly smokes and drinks alcohol. The goal of the analysis is to evaluate the correlation between two of the highest factors that lead to lung cancer. This will be done through using histograms to assess the correlations. The histogram will also take into account whether the patient was lung cancer positive or negative, so we can possibly assess a threshold for these factors.
The second portion will involve developing an interface where users can input requested information about themselves, such as the environments they have been exposed to, their smoking history, and their genetic risk. This information can be inputted as parameters to call a function that processes the user’s information. Inside the function, conditionals will be used to compare the user’s information to the data from actual lung cancer patients and from this determine the likelihood of the patient having or developing the disease. 

Packages used:
Pandas
Matplotlib 

Datasets:
https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link
https://www.kaggle.com/datasets/yusufdede/lung-cancer-dataset\

Considerations:
One consideration is that there are other factors that could contribute to lung cancer risk that are not being taken into account. Also, a correlational study is being done rather than an experiment, which means causation cannot be determined from our analysis. Since correlation is distinct from causation, we cannot attribute any of the risk factors studied as being the cause of lung cancer, and therefore our predictions of whether a person is likely to develop the disease may be inaccurate. Nevertheless, our code will hopefully still be able to provide recommendations to users about lifestyle changes they should make and have some accuracy in determining whether a patient is at high risk.

Expected Results:
If our code is successful, we expect to be able to determine what amount of certian epigenetic factors have the strongest correlation with developing lung cancer and to use these results to predict whether a person is likely to develop lung cancer based on their personal history. We expect that factors such as being exposed to air pollution, smoking frequently, and having high genetic risk will be correlated with an increase in the chance of getting lung cancer. We hope our code can also use the results of our data analysis to warn people that they may have a higher risk of developing the disease, even if it cannot predict with complete certainty whether someone will get lung cancer. The graphical analysis of the data chosen along with the user input component of our project will be able to determine what epigenetic factors have a stronger likelyhood of causing lung cancer for a user based on their personal history.

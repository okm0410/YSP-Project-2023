# YSP-Project-2023

Research Question:
Can we predict whether someone is at risk of developing lung cancer by determining what epigenetic factors are most strongly correlated with having the disease? 

Expected Coding Work:
Our project will have two parts. The first portion will involve analyzing data from patients diagnosed with lung cancer such as how much exposure to air pollution they have had, whether the patient regularly smokes, whether they have genetic predispositions to developing cancer, etc. The goal of the analysis is to evaluate the correlation between each environmental or genetic factor and being diagnosed with lung cancer. This will be done through using scatterplots and lines of best fit to assess the strength of the correlations. Statistical calculations such as the mean, median, and standard deviation of the data sets will also be used to determine trends among lung cancer patients. 
The second portion will involve developing an interface where users can input requested information about themselves, such as the environments they have been exposed to, their smoking history, and their genetic risk. This information can be inputted as parameters to call a function that processes the user’s information. Inside the function, conditionals will be used to compare the user’s information to the data from actual lung cancer patients and from this determine the likelihood of the patient having or developing the disease. 

Possible Packages:
Pandas
Matplotlib 
Numpy

Possible Datasets:
https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link
https://www.kaggle.com/datasets/yusufdede/lung-cancer-dataset
https://www.kaggle.com/datasets/nancyalaswad90/lung-cancer

Considerations:
One consideration is that there are other factors that could contribute to lung cancer risk that are not being taken into account. Also, a correlational study is being done rather than an experiment, which means causation cannot be determined from our analysis. Since correlation is distinct from causation, we cannot attribute any of the risk factors studied as being the cause of lung cancer, and therefore our predictions of whether a person is likely to develop the disease may be inaccurate. Nevertheless, our code will hopefully still be able to provide recommendations to users about lifestyle changes they should make and have some accuracy in determining whether a patient is at high risk.

Expected Results:
If our code is successful, we expect to be able to determine what epigenetic factors have the strongest correlation with developing lung cancer and to use these results to predict whether a person is likely to develop lung cancer based on their personal history. We expect that factors such as being exposed to air pollution, smoking frequently, and having high genetic risk will be correlated with an increase in lung cancer. We hope our code can also use the results of our data analysis to warn people that they may have a higher risk of developing the disease, even if it cannot predict with complete certainty whether someone will get lung cancer. 

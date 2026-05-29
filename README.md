Titanic Data Analysis

 1.Description 
To clean and analyze the Titanic dataset, visualize it, study the factors affecting the survival rate of the passengers and extracting insights from it. Building  machine learning model , Random Forest Classifier, to check whether a passenger survived or not with some given information.

 2.Dataset
The dataset was obtained from kaggle.
The link to the dataset is- https://www.kaggle.com/datasets/yasserh/titanic-dataset.
The dataset contains information about 891 Titanic passengers including age, sex, passenger class, fare and survival status.

 3.Libraries Used
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

 4.Project Steps
1. Data Loading
2. Data Cleaning
3. Data Preprocessing
4. Exploratory Data Analysis and generation of insights
5. Deploying Machine Learning Model ( Random Forest Classifier)

 5.Key Insights
1.  Females survived more because of the " women and children first" evacuation policy. Thus, very less lifeboats remained for men after women and children were evacuated. What we can deduce from this is the number of lifeboats should be increased in every ship.
2. The survival rate for passengers in 1st class was highest followed by passengers in 2nd class and then passengers in 3rd class. As 1st class was located on upper decks, these passengers were closest to the lifeboats. Whereas, the passengers in 3rd class were situated at the very bottom, so navigating up, through all the physical obstacles proved to be difficult. A solution could be providing enough lifeboats to all the levels of the ship. Provision of emergency pathways to the upper deck ensuring quick and smooth moving of passengers from lower to upper deck to ensure safety.
3. Passengers around the age 30 had the maximum survival rate. Children from age 0-10 had a very low survival rate. Also, the survival rate kept on decreasing gradually after 30 reaching almost zero at age 80. This could happen as the older people were not able to respond to the panic and evacuation plan. Their bodies could not support them. For children, the families refuse to split their members. This could be solved by allocating special crew members to handle older people or having better emergency paths for lifeboats to avoid physical obstacles. More children could had been saved if lifeboats could have been filled to its maximum capacity ( because of families refusing to split).                         
4.  Passengers paying higher fares had a higher survival rate. This implies the same thing: higher fares (higher ticket prices) mean 1st class which means higher survival rate as it was present at the top of the deck having easier access to the lifeboats.

 6.Model Accuracy
Random Forest Classifier model has been used on this dataset achieving accuracy of 82.12% 

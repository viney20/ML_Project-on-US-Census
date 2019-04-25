# ML_Project-on-US-Census
United State Census  The data here is for the "Census Income" dataset, which contains data on adults from the 1994 census. This data is labeled with whether the person's yearly income is above or below $50K (and you are trying to model and predict this). Prerequisites: We would highly recommend that before the hack night you have some kind of toolchain and development environment already installed and ready. If you have no idea where to start with this, try a combination like: Python scikit-learn / sklearn Pandas NumPy matplotlib An environment to work in - something like Jupyter or Spyder For Linux people, your package manager should be able to handle all of this. If it somehow can't, see if you can at least install Python and pip and then use pip to install the above packages.  Objectives in this project: Perform data cleaning on the dataset Make a EDA report   Visualize the distributions of various features and correlations between them Feature engineering to extract the correct features for the model Build a classification model based on the features that you select  to predict if the income is above $50k or not. Dataset: The dataset is in the form of a csv file and the link to download is given below: Link: https://drive.google.com/file/d/1J9yQCKYAtzbO75_ApTNLGUceywQzfm_Y/view  Dataset description: The dataset consist of 32562 rows and 14 features .The description of each feature is given below: Listing of attributes:  >50K, &lt;=50K.  age: continuous.  workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.  fnlwgt: continuous.  education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.  education-num: continuous.  marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.  occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.  relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.  race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.  sex: Female, Male.  capital-gain: continuous.  capital-loss: continuous.  hours-per-week: continuous.  native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad &amp; Tobago, Peru, Hong, Holand-Netherlands.  WorkFlow: The workflow for the project is described in  steps given below: Perform data cleaning using pandas library. Which includes replacing the miscoded information and handling missing data. Make a Exploratory Data Analysis on the data using pandas. Visualize distributions and correlation of features using seaborn and pandas Build a classification model for the classification of income. Try different classifiers and compare the accuracy of all the classifiers.
